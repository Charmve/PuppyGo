# PuppyGo

Vision language model and large language model powered embodied agent.

<div>
  <p>
    <img src="src/voxposer.gif" width=430>
    <img src="src/puppygo.jpg" width=320>
  </p>
</div>

## Here’s what I did:

- Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents
- extracts affordances and constraints from large language models and vision-language models to compose 3D value maps, which are used by motion planners to zero-shot synthesize trajectories for everyday manipulation tasks.
- combine with e2e large model trainning framework, like UniAD;


## This Package Is Sponsorware 💰💰💰

[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/Charmve?frequency=one-time&sponsor=Charmve) https://github.com/sponsors/Charmve?frequency=one-time&sponsor=Charmve

This repo was only available to my sponsors on GitHub Sponsors until I reached 15 sponsors.

Learn more about **Sponsorware** at [github.com/sponsorware/docs](https://github.com/sponsorware/docs) 💰.


![image](https://github.com/Charmve/PuppyGo/assets/29084184/3577e267-53a0-4904-909f-6733995e892e)


<br>

## Execution under Disturbances

Because the language model output stays the same throughout the task, we can cache its output and re-evaluate the generated code using closed-loop visual feedback, which enables fast replanning using MPC. This enables VoxPoser to be robust to online disturbances.
      
<div class="columns">
  <div class="column has-text-centered">
    <video id="dist1" controls="" muted="" autoplay="" loop="" width="99%">
      <source src="src/sort-trash-to-tray-dist.mp4" type="video/mp4">
    </video>
    <p style="text-align:center">
      "Sort the paper trash into the blue tray."
    </p>
  </div>

  <div class="column has-text-centered">
    <video id="dist2" controls="" muted="" autoplay="" loop="" width="99%">
      <source src="src/close-top-drawer-dist.mp4" type="video/mp4">
    </video>
    <p style="text-align:center">
      "Close the top drawer."
    </p>
  </div>
</div>
