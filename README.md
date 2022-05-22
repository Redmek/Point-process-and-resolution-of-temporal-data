# Point-process-and-resolution-of-temporal-data

Over the last few decades, the amount of data available on certain very liquid
markets has allowed the development of the field of high frequency finance. Indeed,
the challenge is to model and calibrate the micro structure of the markets as
precisely as possible, and this obviously involves modeling the arrival of different
events by taking into account the finest details. Until the 1990s, market dynamics
were largely described by discrete-time models. Hasbrouck, Engle and Russel
suggested the use of point processes in order to model financial data in a continuous
way in time. In this context, they introduced the ACD model by representing the
point processes by means of their intensity function which also aim to illustrate
the conditional probabilities of arrival of different events on the market in the near
future. A.G Hawkes introduced Hawkes processes during the 1970’s to describe
seismic events. The arrival of a wave was thus modeled using a Poisson process
whose intensity depends on past historical data, thus the latter increases as it goes
along and thus becomes important when an earthquake has just taken place. This
property of historical dependence as well as the simplicity and flexibility of these
processes have led to the use of Hawkes processes in the field of high frequency
finance. This study was first introduced by Bowsher who suggested a Hawkes
process model to describe the joint dynamics of trades and mid-price changes at
the NYSE. During our study, we will place ourselves in the framework of Hawkes’
model. The aim of our study is to study the effect of randomization on statistical
inference in the framework of Hawkes processes. Indeed, in high frequency finance,
the temporal data to be modeled often require a very fine resolution and can lead to
the arrival of two events at the same time.
It is in this context that the randomization procedure comes into play in order to
select the event to keep. We will first study these processes from a mathematical
point of view, both in one dimension and in multidimensional, this study will allow
us to simulate and estimate the different parameters of our model numerically.
Afterwards, we will perform experiments to illustrate the impact of randomization.
To do so, we reduce the quality of the simulated data, first by naive rounding, then
by discretization of a temporal grid with variable time step, in order to study the
impact on the different parameters obtained by estimation.
