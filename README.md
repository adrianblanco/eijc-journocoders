<img src="img/journocoders.png" alt="alt text" width="800">

# Building VR journalism

Virtual reality is in tons of conversations of journalism but very few media have really tested this technology.

In this session we will review some of the examples out of there, take a look to some of the most interesting tutorials and will put our hands on one interesting tutorial during the session..

## First steps: What you will learn

### The core of VR

* [WebGL](https://www.chromeexperiments.com/webgl): a web technology that brings hardware- accelerated 3D graphics to the browser without installing additional software.

* [Three.js](https://threejs.org): A JavaScript 3D Library which makes WebGL simpler.

### You will put your hands on...

* Terminal: Don't be afraid. We will start a localhost from the Terminal.

* Python: We will build our local server in Python. You can do it also with MAMP, xxx, xxx

* HTML&CSS: To build the structure in which we will write our Three.js script.

* D3: in case you follow vr charts tutorial.

## Before starting with Three.js and WebGL
We have to start up a webserver to serve our page and assets.

Open the terminal on your computer (Bash in windows) and navigate to the folder in which you'll build this tutorial. Enter the following at the prompt:

```bash
$ cd /data/vr_interactives # or the folder where you want to build your vr project
$ python -m SimpleHTTPServer
```

If you're using Python 3, you have to run http.server instead.

```bash
$ cd /eijc-journocoders  # or the folder where you want to build your vr project
python3 -m http.server
```

To check that everything is working, go to your local server 8000 [http://localhost:8000/three-demo.html](http://localhost:8000/three-demo.html). That page will be blank for now.

## The tutorials

### LA TIMES vr interactive three.js

In this tutorial you'll learn how we used NASA satellite imagery and elevation data to create a 3-D rendering of the [Gale Crater](http://graphics.latimes.com/mars-gale-crater-vr/) on Mars.

To follow the tutorial go to [their repository](https://github.com/datadesk/vr-interactives-three-js).

You can check the code commented by Journocoeers.

### WSJ virtual reality data visualization

In this tutorial you can learn how to create virtual reality charts. It is written by Roger Kenny, an interactive designer at the Wall Street Journal.

To follow the tutorial go to [this article](http://www.storybench.org/how-to-make-a-simple-virtual-reality-data-visualization/) .

You can check the code commented by Journocoeers.

### Building VR with A-frame
A-frame is a web framework for building virtual reality experiences. Simpler than the ones above, another way to start in VR.

To follow the tutorial go to [this presentation](https://belen-albeza.github.io/building-vr/#7)
