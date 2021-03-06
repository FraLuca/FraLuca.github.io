
<div align="center">
<h1>Space-Time-Separable Graph Convolutional Network for Pose Forecasting - ICCV'21</h1>
<h3> <i>Theodoros Sofianos†, Alessio Sampieri†, Luca Franco and Fabio Galasso</i></h3>
 <h4> <i>Sapienza University of Rome, Italy</i></h4>
</div>

--------


[Abstract](https://fraluca.github.io/#abstract){: .btn .btn-blue .mr-2}
[Paper](https://arxiv.org/abs/2110.04573){: .btn .btn-blue .mr-2}
[Poster and Slides](https://fraluca.github.io/#poster-and-slides){: .btn .btn-blue .mr-2}
[Talk](https://youtu.be/tQIygtJrrtk){: .btn .btn-purple .mr-2}
[More Qualitative Results](https://youtu.be/S8yhxdbN3e4){: .btn .btn-purple .mr-2}
[Code](https://github.com/FraLuca/STSGCN){: .btn .btn-green .mr-2}


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


<iframe src="https://onedrive.live.com/embed?cid=810E56D3DA77514F&amp;resid=810E56D3DA77514F%213969&amp;authkey=APH1cxBycnfMUs0&amp;em=2&amp;wdAr=1.7777777777777777" width="610px" height="367px" frameborder="0">Documento di <a target="_blank" href="https://office.com">Microsoft Office</a> incorporato, con tecnologia <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>




{: .fs-9 }


--------
