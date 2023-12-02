# Consume-ComfyUI-Workflows
This repository contains a collection of `.json` and `.png` files, each representing a unique workflow for [ComfyUI]. Click on the links to view and download the workflow that suits your needs.

## Table of Contents
1. [How To Use](#getting-started)
2. [Workflow List](#workflow-list)
3. [SDXL Turbo to SD1.5 Refiner](#sdxl-turbo-to-sd15-refiner)
4. [Basic First to Last frame interpolation](#first-to-last-frame-interpolation)


## Getting Started

To make things a lot easier to set up, ensure that you have the ComfyUI manager installed. This will allow you to install any missing nodes easily by navigating into the manager and selecting `Install Missing Custom Nodes`
- drag the desired workflow into the ComfyUI interface
- selecting the missing nodes from the list
- head into the ComfyUI Commandline/Terminal and Ctrl+C to shut down the application
- start ComfyUI back up and the software should now have the missing node
- note, some workflows may need you to also download models specific to their workflows... I'll try to leave info on this if necessary

The ComfyUI manager can be install from this repo:
`https://github.com/ltdrdata/ComfyUI-Manager`
To install the manager simply:
- navigate into the custom nodes directory `ComfyUI/custom_nodes`
- `git clone https://github.com/ltdrdata/ComfyUI-Manager.git` in your commandline or terminal. 

## Workflow List

Here is a list of the available workflows:

## SDXL Turbo to SD1.5 Refiner 
(or model of your Choice)
![Basic SDXL Turbo With Refiner Pass Output](./assets/sdxl_w_refiner/00/output.gif)
- [Basic SDXL Turbo With Refiner Pass](./assets/sdxl_w_refiner/00/basic_turbo_w_refiner.json) - This workflow is a basic introduction to the refinement of SDXL turbo outputs. It passes the output of SDXL to as model of your choice, be it SD1.5, SD2.1, or SDXL. This is a very basic but powerful introduction and more workflows and version will be released expanding on this idea. I have released a basic version of this with the intention of acting as an introduction to the community.

<br>
<br>
<br>

## First to Last Frame Interpolation
<p align="center">
  <img src="./assets/frame_interpolation/00/output.gif" alt="Basic Frame Interpolation Output" width="50%">
</p>

- [Frame Interpolation Between Two Images](./assets/frame_interpolation/00/basic_first_last_interpolation.json) - This workflow is a basic introduction to blending between two different frames. This will be expanded on heavily but to get everyone started, I am beginning with this basic yet extremely powerful workflow. 






