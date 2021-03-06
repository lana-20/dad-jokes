| [Dad Jokes](https://github.com/lana-20/50_Projects_in_50_Days/tree/main/DadJokes) | [Live Demo](https://lana-20.github.io/dad-jokes/) |
|----|----|

In this project, I am building a dad joke application where it gives you a joke.
You can click a button to get a new joke, and you can keep getting new jokes.

I am achieving this by making HTTP requests to a third party [API](https://icanhazdadjoke.com/api).
I am using [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) that is built into the browser to make a request and get an object with 
an id, a joke and a status.
And I am taking that joke and putting it into the application.
The code shows how to use Fetch normally, as well as with Async/Await.

Using Fetch is not mandatory, you can use the curl terminal program, Postman or Axios.
Fetch is convenient because it's built into the browser and requires no CDN installation.
