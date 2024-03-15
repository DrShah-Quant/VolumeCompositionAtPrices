 <h1>VolumeCompositionAtPrices</h1>

<h2>Description</h2>
 This Python program visualizes the breakdown of trading volume by transaction type (sell, buy, and open) at each price point recorded during a trading day.
<br />


<h2>Languages and Libraries Used</h2>

- <b>Python</b> 
- <b>Matplotlib</b>
- <b>NumPy</b>
- <b>CSV</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b>
- <b>Jupyter Notebook</b>

<h2>Program walk-through:</h2>

<p align="justify"> The example run presented here is from a Jupyter Notebook environment. You can run the files (ChartV2.ipynb and ChartV3.ipynb) using Ctrl+Enter key presses at the end of each script. Alternatively you can run the python scripts <i>ChartV2.py </i> and <i>ChartV3.py</i> using command <i>python ChartV2.py</i> or <i>python ChartV3.py</i> in a command line if you have python installed properly. The program is depended on a CSV file containing stock transactions raw data. In the example presented below, I have used raw data provided by M+ Securities, a Malaysian stock broker. The raw data contains comma separated values organized into the following colums: "Time","Type","Price","Chg","Vol","Value". "Time" is the time when the transaction occured. "Type" refers to the type of transaction such as buy, close, and open. "Price" refers to the price the share was transacted. "Chg" refers to the difference from the previous price. "Vol" refers to the transaction volume measured in lot sizes (1 lot = 100 shares). And finally "Value" refers to the value of the trasaction (i.e. no of shares x share price). </p>

<p align="center">
Sample CSV raw data : <br/>
<img src="https://i.imgur.com/ZwC3mJi.png" height="80%" width="80%" />
<br />
 <br/>
Launch the Program and enter CSV data file location: <br/>
<img src="https://i.imgur.com/qT5VkVk.png" height="80%" width="80%"/>
<br />
<br />
ChartV2:  <br/>
<img src="https://i.imgur.com/75ix5TP.png" height="80%" width="80%" />
<br />
<br />
ChartV3: <br/>
<img src="https://i.imgur.com/rHodT8Y.png" height="80%" width="80%" />
<br />
 <p align="justify">  The 3D charts above show variations illustrating buy, sell, and open volumes at each price level for each trading day. These disections allow the 3D charts to highlight the activity regions of buyers and sellers. Strong support and resistence regions with heavy buyers and sellers presence, respectively, can be identified from the charts. Through the decomposition charts we can also see the dominating party (buyer or seller) on each day's volume. We can also further analyze the relative strength between buyers and sellers across price levels and time periods. The information provided by ChartV2 and ChartV3 is similar except the presentation is different -- ChartV3 is clearer since it stacks buy, sell, and open.</p>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

