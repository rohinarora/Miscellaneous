* By default, pd.read_csv assumes 1st line as header. Can stop that via header=None. Can pass custom header via ```names=```.
For eg
```
commonHeader=['GPU','Model','Metric','Value']
pd.read_csv('./Total_Inference_Time.csv',sep=' ',names=commonHeader)
```
