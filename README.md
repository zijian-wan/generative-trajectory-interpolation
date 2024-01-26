# Generative trajectory interpolation
This is a trajectory interpolation model based on long short-term memory (LSTM) and generative adversarial network (GAN) that takes as an input a trajectory containing a gap (i.e., a sequence of missing tracking points) and outputs the interpolated complete trajectory.
![](https://github.com/zijian-wan/generative-trajectory-interpolation/blob/0153c07860be5797e2c8c809f5b01c25c3a283ce/figures/archt.png)

**Citation info:**
> Wan, Z., & Dodge, S. (2023, November). A Generative Trajectory Interpolation Method for Imputing Gaps in Wildlife Movement Data. In Proceedings of the 1st ACM SIGSPATIAL International Workshop on AI-driven Spatio-temporal Data Analysis for Wildlife Conservation (pp. 1-8).

## Abstract
Advances in tracking technologies have resulted in growing repositories of large and long-term movement data of wildlife at an unprecedented rate. Nevertheless, many of these movement datasets come with missing records, termed gaps in this paper, which need to be imputed before further movement analysis. However, existing trajectory interpolation methods have certain limitations. Their effectiveness might be restrained by users' domain knowledge of the moving entity or by the properties of the trajectories, to name a few. Moreover, the uncertainty of movement data has not received enough attention and is often neglected in the interpolation process. A review of existing literature suggests a need for designing more robust and broadly applicable data-driven interpolation methods that can self-adapt to the subject tracking data, and meanwhile, can take movement uncertainty into consideration. This study proposes a new trajectory interpolation model that leverages a generative adversarial network (GAN) architecture supported by long short-term memory (LSTM) layers to interpolate missing trajectory points. The model uses a latent code in addition to the noise input to deal with the uncertainty in movement behaviors. We apply and evaluate the proposed model against a real-world GPS trajectory dataset of migratory white storks to assess its effectiveness for imputing migration paths.
