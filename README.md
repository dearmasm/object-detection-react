# "Coke & GreenCup" Detection AI App

Node.js client-side React App that uses **TensorFlow** model generated to recognize differences between a Coke bottle and a Green cup. You can find an in depth walkthrough for training a TensorFlow.js model [here](https://github.com/cloud-annotations/training/). Model generated using **IBM's AI Machine-Learning (ML)** cloud technology.

![](docs/_images/coke+cup_1.png)

## Setup
`git clone` the repo and `cd` into it by running the following command:

```bash
git clone https://github.com/cloud-annotations/object-detection-react.git
cd object-detection-react
```

### `npm install`

> **Note: You’ll need to have Node 8.10.0 or later on your local development machine.** You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

## (Optional Step) Add your own custom TensorFlow.js Model to the App
As example already comes with built-in model inside `public` directory, you do not need to create a model for intial use and testing. If you decide to generate a TensorFlow model using instructions referenced at the top of this documentation, then copy the `model_web` directory generated from the object detection walkthrough and paste it into the `public` folder of this repo.

## Run the App
### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## More Example Tests

![](docs/_images/coke+cup_3.png)
![](docs/_images/coke+empltyglass.png)
![](docs/_images/coke+iphonecoke.png)
![](docs/_images/coke+iphonecup.png)


