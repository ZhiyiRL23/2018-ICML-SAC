# 2018-ICML-SAC-Technical Scheme and Lab Report

## 2018-ICML-SAC-Introduction 



## 2018-ICML-SAC-Experiment

### Experimental Setup

​	Experiments are conducted in MuJoCo, a high-dimensional and continuous action control benchmark for robotic tasks. Specifically, we evaluate the algorithm on Hopper, Walker2d, Humanoid, Swimmer, HalfCheetah, and Ant, as shown in the following figure:

<div style="display: flex; text-align: center; gap: 1px;">
    <figure style="flex: 1;">
        <video src="./assets/Hopper-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Hopper</figcaption>
    </figure>
    <figure style="flex: 1;">
		<video src="./assets/Walker2d-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
		<figcaption>MuJoCo-Walker2d</figcaption>
	</figure>
    <figure style="flex: 1;">
        <video src="./assets/Humanoid-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Humanoid</figcaption>
    </figure>
    <figure style="flex: 1;">
		<video src="./assets/Swimmer-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
		<figcaption>MuJoCo-Swimmer</figcaption>
	</figure>
    <figure style="flex: 1;">
        <video src="./assets/HalfCheetah-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-HalfCheetah</figcaption>
    </figure>
    <figure style="flex: 1;">
		<video src="./assets/Ant-v5.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
		<figcaption>MuJoCo-Ant</figcaption>
	</figure>
</div>

The hyperparameter settings for SAC are as follows:

| SAC  Hyperparameters | Value |
| -------------------- | ----- |
|                      |       |
|                      |       |
|                      |       |
|                      |       |
|                      |       |
|                      |       |
|                      |       |
|                      |       |
|                      |       |



### Performance Analysis of SAC

#### Performance Analysis of SAC on MuJoCo

<div style="display: flex; text-align: center; gap: 1px;">
    <figure style="flex: 1;">
        <img src="./assets/Hopper-v5_online.png" alt="Hopper-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
        <figcaption>MuJoCo:Hopper</figcaption>
    </figure>
    <figure style="flex: 1;">
		<img src="./assets/Walker2d-v5_online.png" alt="Walker2d-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Walker2d</figcaption>
	</figure>
    <figure style="flex: 1;">
		<img src="./assets/Humanoid-v5_online.png" alt="Humanoid-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Humanoid</figcaption>
	</figure>
</div>
<div style="display: flex; text-align: center; gap: 10px;">
    <figure style="flex: 1;">
		<img src="./assets/Swimmer-v5_online.png" alt="Swimmer-v5_online" width="90%;"   oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Swimmer</figcaption>
	</figure>
    <figure style="flex: 1;">
        <img src="./assets/HalfCheetah-v5_online.png" alt="HalfCheetah-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;" />
		<figcaption>MuJoCo: HalfCheetah</figcaption>
	</figure>
    <figure style="flex: 1;">
        <img src="./assets/Ant-v5_online.png" alt="Ant-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;" />
		<figcaption>MuJoCo: Ant</figcaption>
	</figure>
</div>

:golf: **Performance Demonstration of SAC-office**

<div style="display: flex; text-align: center; gap: 1px;">
    <figure style="flex: 1;">
        <video src="./assets/Hopper-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Hopper SAC-office</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Walker2d-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Walker2d SAC-office</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Humanoid-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Humanoid SAC-office</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Swimmer-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Swimmer SAC-office</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/HalfCheetah-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-HalfCheetah SAC-office</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Ant-v5-SAC-office.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Ant SAC-office</figcaption>
    </figure>
</div>

:grinning: **Performance Demonstration of SAC-self**

<div style="display: flex; text-align: center; gap: 1px;">
    <figure style="flex: 1;">
        <video src="./assets/Hopper-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Hopper SAC-self</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Walker2d-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Walker2d SAC-self</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Humanoid-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Humanoid SAC-self</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Swimmer-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Swimmer SAC-self</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/HalfCheetah-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-HalfCheetah SAC-self</figcaption>
    </figure>
    <figure style="flex: 1;">
        <video src="./assets/Ant-v5-SAC-self.mp4" width="90%" controls autoplay loop oncontextmenu="return false;" ondragstart="return false;"></video>
        <figcaption>MuJoCo-Ant SAC-self</figcaption>
    </figure>
</div>



### Hyperparameter Analysis of SAC

#### Learning Rate - Analysis of SAC on MuJoCo

<div style="display: flex; text-align: center; gap: 1px;">
    <figure style="flex: 1;">
        <img src="./assets/Hopper-v5_online_lr.png" alt="Hopper-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
        <figcaption>MuJoCo:Hopper</figcaption>
    </figure>
    <figure style="flex: 1;">
		<img src="./assets/Walker2d-v5_online_lr.png" alt="Walker2d-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Walker2d</figcaption>
	</figure>
    <figure style="flex: 1;">
		<img src="./assets/Humanoid-v5_online_lr.png" alt="Humanoid-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Humanoid</figcaption>
	</figure>
</div>
<div style="display: flex; text-align: center; gap: 10px;">
    <figure style="flex: 1;">
		<img src="./assets/Swimmer-v5_online_lr.png" alt="Swimmer-v5_online" width="90%;"   oncontextmenu="return false;" ondragstart="return false;"/>
		<figcaption>MuJoCo: Swimmer</figcaption>
	</figure>
    <figure style="flex: 1;">
        <img src="./assets/HalfCheetah-v5_online_lr.png" alt="HalfCheetah-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;" />
		<figcaption>MuJoCo: HalfCheetah</figcaption>
	</figure>
    <figure style="flex: 1;">
        <img src="./assets/Ant-v5_online_lr.png" alt="Ant-v5_online" width="90%;"  oncontextmenu="return false;" ondragstart="return false;" />
		<figcaption>MuJoCo: Ant</figcaption>
	</figure>
</div>





























