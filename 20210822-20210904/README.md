### 意见性分享

- **关于论文迭代修改**
  
  [Matthias Niessner](https://twitter.com/MattNiessner)
  
  **Research can be quite brutal when a paper gets rejected.**
  
  Successful groups have the problem with many rejected submissions; but they don't give up, take reviewer feedback, and keep improving their work until it's ready for publication. Key is to recognize what was missing.
  
  **Abdullah Hamdi:** How to deal with deteriorating motivation to work on rejected papers and to ignore the exciting new topics that are emerging all the time?
  
  **Alessandro Saccon:** Even unsuccessful groups face the same issue. Just the key idea is neither good nor new enough, and their paper will never get accepted or less cited. So the real question for me is: how do you get a great idea?
  
  reference: https://twitter.com/MattNiessner/status/1429856784420900868?s=20
  
  
  
***
### 课程和报告分享

#### Symposium on Computer Animation 2021

##### original twitter link（from Michiel van de Panne）：
https://twitter.com/Mvandepanne/status/1429182659859820548

##### webpage：
http://computeranimation.org/program.html#Session1

##### location & time：

September 7-10,2021. Online.

registration web: [http://computeranimation.org/#Registration](https://t.co/3P1KvcK6gf?amp=1)

##### 计算机动画相关论文报告会

***
#### Geometric Deep Learning - Algorithms

##### original twitter link（from Isaac Newton Institute）:
https://twitter.com/NewtonInstitute/status/1430084967858589715?s=20

##### webpage:
https://www.newton.ac.uk/seminar/20210824100011001/

##### location & time:
24 August 2021 – 10:00 to 11:00

##### video page:
https://www.youtube.com/watch?v=9mOX_JbVTNY&ab_channel=INISeminarRoom1

##### 几何深度学习算法

***




### 成果推荐及讨论


- ##### [Seungbae Bang](https://twitter.com/Seungbae13)
  **Happy to announce our "Complementary Dynamics" source code is now publicly available.**
  
  <div align=center><img src="https://github.com/seungbaebang/complementary-dynamics-cpp/blob/master/showcases/elephant_arap.gif" alt="Cover" width="75%"/></div>
  
  Matlab repo: https://github.com/ErisZhang/complementary-dynamics
  
  C++ repo: https://github.com/seungbaebang/complementary-dynamics-cpp

  reference: https://twitter.com/Seungbae13/status/1429905759270277131?s=20
  
- ##### [Tomasz Malisiewicz](https://twitter.com/quantombone)
  **3D Reconstruction from public webcams**
  
  Hey @AmirRubin, check out this 3D #computervision project which uses SuperGlue, a deep feature-based matcher—extremely useful for creating a robust #digitaltwin of outdoor spaces. Thanks @ducha_aiki for sharing!

  <div align=center><img src="https://pbs.twimg.com/media/E9jm_PyX0Bwm06X?format=jpg&name=small" alt="Cover" width="75%"/></div>
  
  abs: https://arxiv.org/abs/2108.09476
  
  - **Amir Rubin:** I love this! SuperGlue and deep front ends are game changers for 3D reconstruction. The robustness of learned features+homography is bringing digital twin creation into the hands of non-expert users. I mean, I’m not talking metaverse scale just yet but who knows?

  - **Noé:** Wow indeed, this is wild. It's the difference between an idea not working at all, and working quite well. There have to be ideas from the past which did not pan out that have to be re-investigated! Do you have insights on use-cases where it made a large difference?

  <div align=center><img src="https://pbs.twimg.com/media/E9lPVSAWEAg28Fi?format=jpg&name=small" alt="Cover" width="75%"/></div>
  reference: https://twitter.com/quantombone/status/1430146858773630994?s=20

- ##### [Thiemo Alldieck](https://twitter.com/thmo_a)
  **imGHUM: Implicit Generative Models of 3D Human Shape and Articulated Pose**
  
  pdf：https://arxiv.org/pdf/2108.10842.pdf
  
  code：https://github.com/google-research/google-research/tree/master/imghum
  
  imGHUM shares it parameterization with the explicit body model GHUM (https://github.com/google-research/google-research/tree/master/ghum). But imGHUM is a SDF, thus fitting to point clouds is straight-forward and fully differentiable. Here we use imGHUM to recover pose and shape parameters of (partial) scans. 
  
  ![Image](https://pbs.twimg.com/media/E9nrF7cXIAILtXt?format=jpg&name=900x900)
  The implicit semantics returned by imGHUM allows e.g. for surface coloring or texturing. Together with the signed distance they are also a 4D descriptor of points in space.
  
  <div align=center><img src="https://pbs.twimg.com/media/E9nrxNeXIAAi8hY?format=jpg&name=900x900" alt="Cover" width="50%"/></div>
  imGHUM generalizes well to novel shapes and poses. We provide gender-neutral, male and female imGHUM models of the full body, head, left and right hand. 
  
  <div align=center><img src="https://pbs.twimg.com/media/E9nspWNXoAMLF1Q?format=jpg&name=900x900" alt="Cover" width="70%"/></div>
  
- ##### [Tomasz Malisiewicz](https://twitter.com/quantombone)
  **DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras**
  
  pdf: https://arxiv.org/abs/2108.10869
  
  The method uses recurrent iterative updates of camera pose and pixelwise depth through a Dense Bundle Adjustment layer. Runs in real-time with two 3090 GPUs.
  
  ![Image](https://pbs.twimg.com/media/E9mxwLCXoAMYa6q?format=jpg&name=900x900)