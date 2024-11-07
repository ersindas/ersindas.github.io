---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
</tbody></table>
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
             <td style="padding:20px;width:30%;vertical-align:top">
              <img src='/files/robot.jpg' width="250">
               <br> 
               <br>
               <br>
               <br>
                 <img src='/files/3DOF_v1-eps-converted-to-1.png' width="250">
            </td>
            <td style="padding:20px;width:80%;vertical-align:middle">
              <a href="https://arxiv.org/pdf/2401.01881">
                  <papertitle><strong>Robust Control Barrier Functions using Uncertainty Estimation with Application to Mobile Robots</strong></papertitle>
              </a>
              <br>
             <strong>Ersin Daş</strong>, Joel W. Burdick
              <br>
              <br>
<!--               href="https://arxiv.org/pdf/2401.01881">Paper</a>
              <p></p> -->
              <p>This paper proposes a safety-critical control design approach for nonlinear control affine systems in the presence of matched and unmatched uncertainties. Our constructive framework couples control barrier function (CBF) theory with a new uncertainty estimator to ensure robust safety. The estimated uncertainty with a derived upper bound on the estimation error is used for synthesizing CBFs and safety-critical controllers via a quadratic program-based feedback control law that rigorously ensures robust safety while improving disturbance rejection performance. The method is extended to higher-order CBFs (HOCBFs) to achieve safety under unmatched uncertainty, which may cause relative degree differences with respect to control input and disturbances. We assume the relative degree difference is at most one, resulting in a second-order cone constraint. The proposed robust HOCBF method is demonstrated via a simulation of an uncertain elastic actuator control problem. Finally, we experimentally demonstrated the efficacy of our robust CBF framework on a tracked robot with slope-induced matched and unmatched perturbations.</p>
              <center> <img src='/files/methods-eps-converted-to-1.png' width="480"> </center>
  </td>
</tbody></table>

<br> <!-- New line --> 
<br> <!-- New line --> 
<br> <!-- New line --> 

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
</tbody></table>
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
             <td style="padding:20px;width:30%;vertical-align:top">
              <img src='/files/zmp_4cdc-eps-converted-to-1.png' width="250">
               <br> 
               <br>
               <br>
               <br>
                 <img src='/files/PSSf-eps-converted-to-1.png' width="250">
            </td>
            <td style="padding:20px;width:80%;vertical-align:middle">
              <a href="https://arxiv.org/abs/2403.08916">
                  <papertitle><strong>Rollover Prevention for Mobile Robots with Control Barrier Functions: Differentiator-Based Adaptation and Projection-to-State Safety</strong></papertitle>
              </a>
              <br>
             <strong>Ersin Daş</strong>, Aaron D. Ames, Joel W. Burdick
              <br>
              <br>
<!--               href="https://arxiv.org/pdf/2401.01881">Paper</a>
              <p></p> -->
              <p>This paper develops rollover prevention guarantees for mobile robots using control barrier function (CBF) theory, and demonstrates the method experimentally. We consider a safety measure based on a zero moment point condition through the lens of CBFs. However, these conditions depend on time-varying and noisy parameters. To address this issue, we present a differentiator-based safety-critical controller that estimates these parameters and pairs Input-to-State Stable (ISS) differentiator dynamics with CBFs to achieve rigorous safety guarantees. Additionally, to ensure safety in the presence of disturbances, we utilize a time-varying extension of Projection-to-State Safety (PSSf). The effectiveness of the proposed method is demonstrated via experiments on a tracked robot with a rollover potential on steep slopes.</p>
              <center> <img src='/files/experiment-eps-converted-to-1.png' width="380"> </center>
  </td>
</tbody></table>
