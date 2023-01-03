# ![image](https://user-images.githubusercontent.com/106968663/193465348-dbefd28f-ec35-48e9-a105-24fa745e13ff.png) ai-image :man:

# :smile: Please follow the Link below for the wonderful experience

# [mgai-images](https://mgai-images.onrender.com/)

> This Web app that uses Node.js and OpenAI to generate automated images through SEO.
> Also is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.
> This App is a replicate from the actual API on OpenAI image auto-generator and some modifications was add by me. 🙂

> The MG Musty Image AI is an OpenAI application that enable users to generate images by just typing
> into the search engine box by describing whatever image they want and the AI immediately generates a similar or replicate image.

**Generations**

The image generations endpoint allows you to create an original image given a text prompt.
Generated images can have a size of 256x256, 512x512, or 1024x1024 pixels. Smaller sizes are faster to generate.
You can request 1-10 images at a time using the generate key parameter.
The more detailed the description, the more likely you are to get the result that you or your end user want.

**Caution**

The Image generation does not allow erotic or pornographic search, it is censored and have firewall regulations against such items.

# Front-End Sampling 

![screencapture-localhost-5000-2022-12-15-13_25_22](https://user-images.githubusercontent.com/106968663/207858574-3b0b6d17-ed21-417a-9314-d62d12b38741.png)


# Exhibition

![screencapture-localhost-5000-2022-12-13-20_01_53](https://user-images.githubusercontent.com/106968663/207857930-0d453c73-e7a4-4524-a5f0-6891a4535525.png)

## Usage

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

*  Download (if you don`t have Node-Js from the website to your computer)

```bash
download node-js
```

* Install the dependencies

```bash
npm install
```

* Run commands (install package.son)

```bash
npm init -y
```

* Install (express and openai environment)

```bash
npm i express openai dotenv
```

* To keep server running (no need for update)

```bash
npm -D nodemon
```

* Then edit your package.json file.

* To start the server run

```bash
npm run dev
```

* OR Run server

```bash
npm start
```

# Create an OpenAI API-KEY 
* Create a file Example.env for the OpenAi API you have to follow;

> You have to go to OpenAI site and create an account, after creating the account go to settings and check for key-creation and then you can copy your key and paste it at the API-Key in the env file. 

> But when pushing it to github, you need to remove the key, cause is a secret key, which automatically OpenAI will dictate that your key is on public site and they will automatically disable the key, you have to create another one for the application to render. 

> But on your local computer is safe and if you are to deploy the application on a hosting site, you need to put it in an environment variable where is not make visible for the third party to see. 
> That's all you need to do. 

# 📝 Author

[Mustapha Aliyu Galadima](https://github.com/MG-Musty/)
