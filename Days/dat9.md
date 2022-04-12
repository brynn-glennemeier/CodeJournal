# What I learned

## Today we worked with nodemon

We created these servers using node/nodemon. It was pretty simple using these
codes. The way we created them was by running the //app.get code. We made a dice
roll one, a greet one, and a mealTime code. You have to make sure there are
no errors and you also have to make sure that you save the code before reloading
the page or it won't work. always use //(request, response) code and make sure
you look over your code. make sure you also get the express package.

Here is what a route looks like:

//js
app.get("/rockPaperScissors", (request, response) => {
  let r = Math.floor(Math.random() * 3) + 1
  if (r == 1) {
    response.send(["Rock"])
  }
  if (r == 2) {
    response.send(["Paper"])
  }
  if (r == 3) {
    response.send(["Scissors"])
  }
})
//
