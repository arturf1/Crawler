<details open="closed">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#agent-design">Agent Design</a>
      <ul>
        <li><a href="#observation">Observation</a></li>
        <li><a href="#actions">Actions</a></li>
        <li><a href="#reward-function">Reward Function</a></li>
        <li><a href="#training">Training</a></li>
      </ul>
    </li>
    <li><a href="#agent-for-simplified-2048">Agent for Simplified 2048</a></li>
    <li><a href="#agent-for-2048">Agent for 2048</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#resources">Resources</a></li>
    <li><a href="#contact-and-license">Contact & License</a></li>
  </ol>
</details>

## About The Project

## Agent Design 

### Observation

### Actions 

### Reward Function 

![Discounted reward for new highest tile found](Recordings/2048_reward_functions.PNG)

### Training

```sh
   mlagents-learn config/trainer.yaml --run-id=rndLocRndValwNormMask --initialize-from=deterLocDeterValwNormMask
   ```

```sh
   mlagents-learn config/trainer_rndLocRndValNormwMaskSimpleReward.yaml --run-id=rndLocRndValNormwMaskSimpleReward
   ```

## Getting Started

To get started, first install Unity Game Engine from  https://unity.com/. This project also requires the ML Agents extension. Installation instructions can be found on the extension's Github, link below. 
* [Unity ML Agents](https://github.com/Unity-Technologies/ml-agents)

Note: When reusing assets from this project in a new project, be sure that settings in ProjectSettings/DynamicsManager match. 

Once the Engine and ML Agents extension are installed, clone the project repository and import the project using Unity Hub. 

This project also uses the following assets, which are included in the project files. 
* [Gridbox Prototype Materials](https://assetstore.unity.com/packages/2d/textures-materials/gridbox-prototype-materials-129127)

## Resources

### Unity ML Agents

* [Unity Agent Design](https://github.com/Unity-Technologies/ml-agents/blob/release_2_verified_docs/docs/Learning-Environment-Design-Agents.md#masking-discrete-actions)

* [Unity ML Agent Classes](https://docs.unity3d.com/Packages/com.unity.ml-agents@1.0/api/Unity.MLAgents.html)

* [Training Configuration File](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Training-Configuration-File.md#common-trainer-configurations)

### RL

* [Part 1: Key Concepts in RL](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html#reward-and-return)

* [Part 3: Intro to Policy Optimization](https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html#deriving-the-simplest-policy-gradient)

* [Understanding PPO Plots in TensorBoard](https://medium.com/aureliantactics/understanding-ppo-plots-in-tensorboard-cbc3199b9ba2)

## Contact and License

[@arturf124](https://twitter.com/arturf124) | [LinkedIn](https://www.linkedin.com/in/filipowicza/)

MIT License

