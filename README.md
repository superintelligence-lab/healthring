# health_ring
A physical device that can track blood glucose non-invasively using Infrared light, as well as heart rate and blood oxygen using LEDs. The device is paired with a Virtual Reality application composed of three scenes, exerting a calm, horrific or concentrated state of mind respectively. 

# Introduction
By 2050, the number of people aged 80 years and above will more than triple, reaching 400 million individuals. This might sound like good news to toast to with a glass of wine, but each sip from the glass leaves a bitter aftertaste. Starting in the fifth decade of life, humans are at an exponential risk of suffering from chronic conditions and disabilities as time passes. Worldwide, the five biggest risk factors for death are high blood pressure, smoking, high blood glucose, air pollution and obesity in decreasing order. In Finland, high blood glucose levels get the silver medal for being the second biggest risk factor for death. But how do we avoid the hundreds of millions of elderly people seeing nothing but the walls of a hospital or nursing home in their last
decades of life?
One of the leading researchers in the field of aging and genetics, David Sinclair, suggests that anyone, of any age or health status, should continuously monitor one’s body to detect changes and irregularities early and prevent chronic disease. Currently, we track our cars more than ourselves. Although Americans spend just under an hour in their car every day, the car’s technical status is continuously tracked with its dashboard. By contrast, 40 percent of Americans skip at least one recommended medical test or treatment per year, leaving them with limited insights into their health.

According to Sinclair, the most important biomarkers that anyone should continuously track to identify and minimize signs of disease and aging are the following: glucose, heart function, inflammation, cortisol, lactate and blood oxygen. In the context of this project work, we developed a personal gadget measuring some of the
biomarkers mentioned by Prof. Sinclair to analyze the health status of an individual. The selected biomarkers indicate the current health status of a person, with respect to their healthspan, lifespan, biological and chronological age. Specifically, we track the following biomarkers non-invasively: glucose level, blood oxygen and heart rate. The device is not only aimed at individuals at risk or suffering from disease, but also at those who want to extend their mental and physical health to
avoid these scenarios.

The longer an individual’s biomarkers are tracked with the device, the more representative the gained data will be, as all biomarkers change throughout the day and are influenced by sleep, food intake, physical activity, stress and other factors. As the device is quite bulky and fragile at this first iteration, it would be neither handy nor safe enough to track users’ values throughout an entire day. This is why we decided that our device will be coupled with a Virtual Reality (VR)
application. The aim of using VR in combination with our physical device is to get the biggest range of values for each of the biomarkers that we possibly can in a short time window of a few minutes. Of course, this is not a perfect representation of an individual’s fluctuations of these biomarkers during an entire day. For example, food intake has a significant impact on glucose levels and thus, the feeding status of an individual trying our device will have a high impact on his or her glucose levels. However, the VR scenes enable us to easily test the physical device on different people, to find out whether our approach is valid and accurate.

# Code Accessibility and Project Video

The code for the physical device was written in C++ and Python and can be found in this GitHub repository: https://github.com/abolfazljalali/GMeter. The code for making the VR scene was written in C Sharp, as it was created in Unity. The code for the VR Scene can be found in this repository: https://drive.google.com/drive/folders/1PALHec799VSFf-ryc26VIznpf6- rvQI7?usp=sharelink.
A video of a user engaging in our VR Experience while being attached to our physical device is uploaded on YouTube: https://youtu.be/HSj71tfiaZw. The video is split into three scenes. One shows the user in the VR Scene, one displays the real-time values of his heart rate, blood oxygen and blood glucose as captured from our device and the last one displays the user’s current view in the VR scene.
