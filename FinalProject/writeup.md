# CSE 168 Final Project

Group Members - Tarun Murugan and Jonathan Duong

## Project Plan
Throughout the course, we've been fascinated with a variety of rendering techniques and technologies that were covered. After reviewing a majority of them, we decided that we wanted to implement photon mapping into our path tracer. If we are successful in implementing photon mapping we may attempt machine learning powered monte carlo denoising. Although these topics seem completely different we found them most exciting, and reasonable.

## Progress
So far we have implemented photon tracing algorithm that uses russian roullete. We developed this as a preprocessing step for our renderer. We have validated that the photons are accurately collected, but we weren't able to correctly display the photon map. Here are our results. We used the scenes that were provided to use in our previous homeworks, but we plan on trying additional scenes in the future.

### ggx scene

![ggx](./ggx.png)
![ggxPhotonMap](./ggxPhotonMap.png)

### cornellBRDF scene

![cornell](./cornellBRDF.png)
![cornellPhotonMap](./cornellBRDFPhotonMap.png)


## Next Steps
Our next steps are to finish implementing photon transmission into our photon tracing algorithm and implement the photon gathering step in our renderer. Other than the resources provided to us in class, we are using a Stanford course we found online. Here is the link: https://graphics.stanford.edu/courses/cs348b-00/course8.pdf

