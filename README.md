# TwinTurbine-DCDC
This is a group Academic Project for **DCDC** course at Stockholm University, designed to experience a **digital twin** project in immersive technology.
<!--![{Your App XR} logo](./docs/example-image.jpg)-->

<!--information/ **MarkDown** reference is available here: <https://www.markdownguide.org/basic-syntax/>_-->

## 1. Introduction

Welcome to **_TwinTurbine_**, which is a **digital twin** project that lets you experience working with wind turbine in a mixed reality environment.

The proposed solution is valuable for remote monitoring and controlling, and improving turbine's performance.

## 2. Design Process

<!--Evidence on the general overview of how you planned, designed, and developed your project, including the goals, challenges, and solutions._]-->
The design process includes ideation of concepts and interactions, testing of technologies, creation of Unity scene, user testing, iteration, and demonstration. 

### 2.1. Brainstorming:
After some brainstorming, we came up with some ideas for different stages:

- In the first step, we discussed the physical and virtual entities, their connection, and the services and functions we wanted to implement.

<figure style="text-align:center">
    <img src="https://github.com/Mukheem/TwinTurbine/assets/145973209/03e1ef34-4b37-421a-b54a-28db34e8059b" alt="DTComponents" style="max-width:100%;" height="auto">
    <figcaption><i>Digital Twin Components</i></figcaption>
</figure>

<figure style="text-align:center">
    <img src="https://github.com/Mukheem/TwinTurbine/assets/145973209/7ca62bda-072b-40ea-a0ed-361c86724b81" alt="Primary Prototype" style="max-width:100%;" height="auto">
    <figcaption><i>Primary Prototype for physical turbine & virtual model</i></figcaption>
</figure>

- Then, we shared our ideas on how to rotate the servo motor from Arduino and which physical turbine is better to provide.
<figure style="text-align:center">
    <img src="https://github.com/Mukheem/TwinTurbine/assets/145973209/b777cb85-2e86-4cd3-8317-d48586b27ba8" alt="Sketch" style="max-width:100%;" height="auto">
    <figcaption><i>Arduino sketch to rotate the Servo Motor</i></figcaption>
</figure>

<figure style="text-align:center">
    <img src="https://github.com/Mukheem/TwinTurbine/assets/145973209/c1b97fd4-f495-4e54-8c17-a1d949cca986" alt="Wind Turbine" style="max-width:100%;" height="auto">
    <figcaption><i>Servo motor and wind turbine</i></figcaption>
</figure>

- Finally, we focused on the way we want to make the connection between ESP32 and Unity
<figure style="text-align:center">
    <img src="https://github.com/Mukheem/TwinTurbine/assets/145973209/d910c49e-2518-4181-8831-0987415b2977" alt="Communication" style="max-width:100%;" height="auto"></i>
    <figcaption><i>Connecting Unity to Arduino</i></figcaption>
</figure>


### 2.2. User Persona:
- The Project's target users are engineers and technicians who work with wind energy systems and Educational Institutions where the simulator can be used for training purposes. Moreover, the main target group is enterprises interested in immersive technology.
- User Persona: A description of your target user, their needs, motivations, and pain points, and how your project addresses them.
- User Journey: A visualization of how your user interacts with your project, from the initial trigger to the final outcome, and what emotions they experience along the way.
- Wireframes and Prototypes: A collection of sketches, mockups, or prototypes that show the layout, structure, and functionality of your project, and how you tested and iterated on them.


## System description

### Features

[_Features and functionalities of your project. You can use bullet points, screenshots, gifs, or videos to illustrate your points. Also include a link to a demo or a live version of your project._]

For example:

- Immersive and realistic 3D models of [...]
- Interactive and intuitive controls using hand gestures and voice commands
- Customizable settings and preferences for the user experience
- Compatible with various XR platforms and devices

Watch the demo video or try the live version.

Link: <https://extralitylab.dsv.su.se/>

## Installation

[_Installation process to build and run your project. Use code blocks, tables, or lists to show the commands, steps, or requirements the chosen platform. Mention any dependencies or libraries that your project uses and how to install them._]

To install and run [Your app] on your platform or device, follow the instructions below:

| Platform | Device | Requirements | Commands |
| -------- | ------ | ------------ | -------- |
| Windows  | Meta Quest   | Unity 2022.3 or higher, Arduino | `git clone https://github.com/user/repo.git`<br>`cd project-xr`<br>`open MainScene.unity`<br>`Build and Run` |
| Android  | Phone  | Android 19 or higher, ARCore 1.18 or higher | `git clone https://github.com/user/repo.git`<br>`cd solar-system-xr`<br>`open SolarSystemXR.unity`<br>`switch platform to Android`<br>`build and run` |

You also need to install the following dependencies or libraries for your project:

- Library A - a Unity plugin for building VR and AR experiences
- Library B - a C# wrapper for speech recognition and synthesis

## Usage

[_Usage section showing how to use your project and interact with its features. You can use examples, screenshots, gifs, or videos to demonstrate the user interface, controls, and feedback of your project. You can also provide tips, tricks, or best practices for using your project effectively._]

To use [Your App XR} and interact with its features, follow the guidelines below:

- To move around, use the touchpad or the joystick on your controller, or swipe on your phone screen.
- To select ...a planet or a moon, point at it with your controller or your phone, or gaze at it with your headset.
- To zoom in or out, use the trigger or the button on your controller, or pinch on your phone screen.
- To access the information panel, press...
- To use voice commands, say "OK" followed by one of the following phrases:
  - "Show me [X]" - to show X element
  - "Close window Y" - to close window Y
  
Some tips, tricks, and best practices for using [Your App XR} effectively:

- Tip 1
- Tip 2


## References

Acknowledge here the sources, references, or inspirations that you used for your project. Give credit to the original authors or creators of the materials that you used or adapted for your project (3D models, source code, audio effects, etc.)

## Contributors

The authors of the project, contact information, and links to their websites or portfolios.
