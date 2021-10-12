
<div align="center">
<h1>Space-Time-Separable Graph Convolutional Network for Pose Forecasting - ICCV'21</h1>
<h3> <i>Theodoros Sofianos†, Alessio Sampieri†, Luca Franco and Fabio Galasso</i></h3>
 <h4> <i>Sapienza University of Rome, Italy</i></h4>
</div>

--------


[Abstract](https://fraluca.github.io/#abstract){: .btn .btn-blue .mr-4}
[Paper](https://arxiv.org/abs/2110.04573){: .btn .btn-blue .mr-4}
[Poster and Slides](https://fraluca.github.io/#poster-and-slides){: .btn .btn-blue .mr-4}


[Talk](https://youtu.be/tQIygtJrrtk){: .btn .btn-purple .mr-4}
[More Qualitative Results](https://youtu.be/S8yhxdbN3e4){: .btn .btn-purple .mr-4}
[Code](https://github.com/FraLuca/STSGCN){: .btn .btn-green .mr-4}


--------

{: .fs-9 }


<p align="center">
    <img src="/images/pipeline-cameraready-1.png" width="600" alt="centered image" />
</p>

{: .fs-9 }

--------




# Abstract
Human pose forecasting is a complex structured-data sequence-modelling task, which has received increasing attention, also due to numerous potential applications. Research has mainly addressed the temporal dimension as time series and the interaction of human body joints with a kinematic tree or by a graph. This has decoupled the two aspects and leveraged progress from the relevant fields, but it has also limited the understanding of the complex structural joint spatio-temporal dynamics of the human pose.

Here we propose a novel Space-Time-Separable Graph Convolutional Network (STS-GCN) for pose forecasting. For the first time, STS-GCN models the human pose dynamics only with a graph convolutional network (GCN), including the temporal evolution and the spatial joint interaction within a single-graph framework, which allows the cross-talk of motion and spatial correlations. Concurrently, STS-GCN is the first space-time-separable GCN: the space-time graph connectivity is factored into space and time affinity matrices, which bottlenecks the space-time cross-talk, while enabling full joint-joint and time-time correlations. Both affinity matrices are learnt end-to-end, which results in connections substantially deviating from the standard kinematic tree and the linear-time time series.

In experimental evaluation on three complex, recent and large-scale benchmarks, Human3.6M [Ionescu et al. TPAMI'14], AMASS [Mahmood et al. ICCV'19] and 3DPW [Von Marcard et al. ECCV'18], STS-GCN outperforms the state-of-the-art, surpassing the current best technique [Mao et al. ECCV'20] by over 32% in average in the most difficult long-term predictions, while only requiring 1.7% of its parameters. We explain the results qualitatively and illustrate the graph attention by the factored joint-joint and time-time learnt graph connections.

{: .fs-9 }

# Poster and Slides

<p align="center">
    <img src="/images/7726_Poster_page-0001.jpg" alt="centered image" />
</p>

{: .fs-9 }
--------


<iframe src='https://view.officeapps.live.com/op/embed.aspx?src=[https://1drv.ms/p/s!Ak9Rd9rTVg6BnwFOeZIFOYtwzj0d?e=7nPJcr]' width='100%' height='100%' frameborder='0'>




{: .fs-9 }


--------
