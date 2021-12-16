# A description collection of prognostics data sets

### Machine Dataset 1: PHM 2008 [1]
##### Data description
Data from the data challenge competition held at the 1st international conference on Prognostics and Health Management (PHM08) is being made publicly available. The dataset is similar to the one posted above (see Turbofan engine degradation simulation data set) except the true RUL values are not revealed. Users are expected to develop their algorithms using training and test sets provided in the package. The data set was provided by the Prognostics CoE at NASA Ames.[2]

##### Dataset description (Original description from the competition:)
A data set consisting of multiple multivariate time series is provided. This data set is further divided in to training and testing subset. Each time series is from a different instance of the same complex engineered system (referred to as a “unit”) – e.g., the data might be from a fleet of ships of the same type. Each unit starts with different degrees of initial wear and manufacturing variation which is unknown to the user. This wear and variation is considered normal, i.e., it is not considered a fault condition. There are several operational settings that have a substantial effect on unit performance. These settings are also included in the data. The data is contaminated with sensor noise. The unit is operating normally at the start of each time series, and develops a fault at some point during the series. In the training set, the fault grows in magnitude until system failure. In the test set, the time series ends some time prior to system failure. The objective of the competition is to predict the number of remaining operational cycles before failure in the test set, i.e., the number of operational cycles after the last cycle that the unit will continue to operate.

##### Score calculation
Algorithms will be scored based on the error of the predictions for the test set. Predictions far from the target are penalized exponentially. The penalty function is asymmetric, with late predictions penalized more heavily than early predictions (i.e., it is better to predict failure too soon than too late). Lower scores are better; a perfect algorithm would score zero. Check the best performing scores here（https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#phm08_challenge）

Less error and well speed


##### Dataset Citation	
A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA
Reference：
[1] A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA
[2] https://c3.nasa.gov/dashlink/projects/15/





### Machine Dataset 2: PHM 2012 [？]
##### Data description
Data from the data challenge competition held at the 1st international conference on Prognostics and Health Management (PHM08) is being made publicly available. The dataset is similar to the one posted above (see Turbofan engine degradation simulation data set) except the true RUL values are not revealed. Users are expected to develop their algorithms using training and test sets provided in the package. The data set was provided by the Prognostics CoE at NASA Ames.[2]

##### Dataset description (Original description from the competition:)
https://github.com/wkzs111/phm-ieee-2012-data-challenge-dataset/blob/master/IEEEPHM2012-Challenge-Details.pdf

##### Score calculation
Algorithms will be scored based on the error of the predictions for the test set. Predictions far from the target are penalized exponentially. The penalty function is asymmetric, with late predictions penalized more heavily than early predictions (i.e., it is better to predict failure too soon than too late). Lower scores are better; a perfect algorithm would score zero. Check the best performing scores here（https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#phm08_challenge）

Less error and well speed


##### Dataset Citation	
A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA


##### Reference：
[1] A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA




### Machine Dataset 3: Turbofan Engine Degradation Simulation Data Set
(C-MAPSS) [1]
##### Data description
Engine degradation simulation was carried out using C-MAPSS. Four different were sets simulated under different combinations of operational conditions and fault modes. Records several sensor channels to characterize fault evolution. The data set was provided by the Prognostics CoE at NASA Ames.

CMAPSSData数据来源于Turbofan引擎，Turbofan引擎是一种现代的汽油涡轮引擎，NASA空间探索局用的就是这种引擎。

##### Dataset description 

数据集包括每个引擎的时间序列。所有的引擎都是同一类型，但在制造过程中，每个引擎的初期的磨损程度和差异是不同的，这一点用户是不知道的。有三种可选的配置，可用于改变每个引擎的性能。每个引擎有 21 个传感器，当引擎运行时，传感器收集与引擎状态相关的测量数据。收集到的数据中有一些传感器噪声。逐渐地，每个引擎会有一些不足，这些可以从传感器读数中发现。时间序列在发生故障前的某个时间结束。数据包括引擎单元号、时间戳、三种配置以及 21 个传感器读取的数据。



##### Score calculation

Less error and well speed


##### Dataset Citation	
A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA



##### Reference：
[1] A. Saxena and K. Goebel (2008). "PHM08 Challenge Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA
[2] https://www.kaggle.com/behrad3d/nasa-cmaps
[3]https://www.kaggle.com/behrad3d/nasa-cmaps
[4] https://wanzhouyi.github.io/turbofanyin-qing-tui-hua-shu-ju-ji-cmapssdatajian-jie.html
[5] A. Saxena, K. Goebel, D. Simon, and N. Eklund, Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation, in the Proceedings of the 1st International Conference on Prognostics and Health Management (PHM08), Denver CO, Oct 2008.
[6] https://hal.archives-ouvertes.fr/hal-01145003/   
Review and Analysis of Algorithmic Approaches Developed for Prognostics on CMAPSS Dataset























### Battery Dataset 1: Small Satellite Power Simulation Data Set
##### Data description
Experiments on Li-Ion batteries. Charging and discharging at different temperatures. Records the impedance as the damage criterion. The data set was provided by the Prognostics CoE at NASA Ames.

##### Dataset description 


##### Score calculation

Less error and well speed

##### Dataset Citation	
B. Saha and K. Goebel (2007). "Battery Data Set", NASA Ames Prognostics Data Repository (http://ti.arc.nasa.gov/project/prognostic-data-repository), NASA Ames Research Center, Moffett Field, CA


### Aero Dataset 1: Small Satellite Power Simulation Data Set
Data description
Data collected from the simulated experiments on small satellite BP930 batteries using the MACCOR system. Reference document can be dowloaded here. The power cycle reference sheet can be dowloaded here.

##### Dataset description 


##### Score calculation

Less error and well speed

##### Dataset Citation	
Z. Cameron, C. Kulkarni, A. Guarneros, K. Goebel and S. Poll, “A Battery Certification Testbed for Small Satellite Missions”, IEEE AUTOTESTCON 2015, Nov 2-5, 2015, National Harbor, MA



# PHM/故障 数据集总结列表

开源旋转机械故障数据集整理
https://github.com/hustcxl/Rotating-machine-fault-data-set

工业制造领域数据
http://madnet.org:8765/explore.html?t=0.08906464297121186

PHM数据集总结
https://blog.csdn.net/Miraclecanbeachieve/article/details/89516801

NASA 数据集
https://towardsdatascience.com/lstm-autoencoder-for-anomaly-detection-e1f4f2ee7ccf
包含了CMAPSS、PHM2008挑战赛数据集、PHM2012数据集（第十个）、以及其他的几种数据集。

PHM2009数据集：-------https://c3.nasa.gov/dashlink/resources/997/

马里兰大学CALCE锂电池 数据集
https://web.calce.umd.edu/batteries/data.htm

Open rotating mechanical fault data set
https://github.com/hustcxl/Rotating-machine-fault-data-set

