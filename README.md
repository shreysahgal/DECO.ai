<p align="center">
  <img src="https://github.com/shreysahgal/DECO.ai/blob/44d03474c6a0d9f3f03ddf0cad4900ca7599cfb3/static/deco.png" alt="deco_logo" width="300"/>
<h3 align="center"> Effortlessly rearrange your living space without lifting a finger! Use state-of-the-art AI to scan your furniture, create 3D models, and virtually design and visualize your room in a snap.</h3>
</p>

## Inspiration
Decorating is a crucial part of making a house feel like a home, but it can be quite the hassle. DECO.ai was inspired by the significance of rearranging furniture to create a cozy and functional living space. Our team recognized the challenge of visualizing new pieces within a room before committing to buying them. So, leveraging cutting-edge NeRF technology, we developed an app that lets you scan furniture, generate 3D models, and virtually arrange them in your room with ease. This tool not only simplifies interior design decisions, but also serves as a practical shopping companion, allowing users to confidently plan their spaces before making any purchase decisions.

## What it does
DECO.ai comes in two fabulous parts:
### iOS App: DecoGO
DecoGO allows users to use their iOS devices as a virtual 3D scanner. But instead of many scanners today that require fancy sensors like LIDAR or structured light, our app can synthesize high-fidelity 3D models using only a few images. When a user sees a snazzy new piece of furniture, decoration, or anything else, they simply need to take a 30-second video walking around it while keeping it in frame. Once they confirm that their video looks good, they upload their video to their personal collection of objects.
### Desktop App: DecoSim
Once a user has scanned a few objects that they might be interested in, they simply need to log in to their desktop app, which automatically syncs with DecoGO. Once there, they can create a create of specified dimensions and start playing around with different decoration configurations!

## How we built it
The iOS app for our project was built using Flutter. We use a python to process the data and synthesize the object models, and we use Rust and Bevy for the DECO.ai 

## Examples

## Challenges we ran into
The most challenging aspect of this project was by far the implementation of the NeRFs and the synthesis of the 3D models. NeRFs are a fascinating and cutting-edge technology, but that comes with the downside of few existing, well-maintained codebases. We spent a lot of time sifting through various NeRF papers and implementations, many without much success. Thankfully, after a lot of time, we found an API that works for us, with some prerequisite data processing.

## Accomplishments that we're proud of
Our team is most proud of the convergence of innovative technology and real-world problem-solving that we managed to achieve. Implementing NeRFs into a practical application like DECO.ai was definitely a challenge, considering their primary existence in complex research fields like robotics. We recognized a genuine need - the struggle of envisioning furniture within our living spaces - and successfully utilized NeRFs to provide a solution. Moreover, engineering the intricate system design involved in scanning furniture, generating 3D models, and facilitating seamless room design was a testament to our team's dedication and problem-solving skills. It's immensely fulfilling to see our original idea come to life and address a practical problem in such a tangible and user-friendly way.

## What we learned
Undoubtedly, our journey with DECO.ai provided an incredible learning curve for our team. Firstly, delving into NeRFs was an enlightening experience that allowed us to truly grasp their inner workings and intricacies. Understanding how these cutting-edge models functioned under the hood not only expanded our knowledge base but also honed our skills in applying them to solve real-world challenges. Additionally, grappling with CUDA and GPU optimization was a significant learning point, highlighting the complexities involved in fine-tuning performance for such advanced technologies. Moreover, our foray into the Bevy engine introduced us to a new realm of possibilities, unveiling insights into its mechanics and potential applications. Overall, this project served as a comprehensive learning platform, equipping us with hands-on expertise in NeRFs, GPU optimization, and game engine utilization, enhancing our skills for future innovative endeavors.

## What's next for DECO.ai
The future roadmap for DECO.ai is filled with exciting advancements aimed at enhancing user experience and expanding capabilities. Our primary focus involves refining the 3D model generation process by experimenting with diverse NeRF models. This initiative aims to accelerate the generation speed while ensuring cleaner and more accurate output. To facilitate scalability, we're gearing up to acquire additional compute power and fortify the backend infrastructure, ensuring a seamless and robust experience for a growing user base.

Moreover, customization lies at the heart of our plans. We aspire to offer users more creative control by introducing features such as custom floor plans, personalized wallpaper options, and the inclusion of windows. These enhancements will empower users to craft and visualize their spaces with even greater precision and personalization.

