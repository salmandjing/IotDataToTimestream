
# Simulating IoT data into Timestream

Instruction on how to deploy this in your account: [Here](/IotDataToTimestream
/Simulating IoT Devices and Sending it to Timestream.pdf)

This blog shows how you can simulate IoT devices and capture/filter that data for your own visualization tools. In 30 minutes you will
-	Use a [CloudFormation](https://docs.aws.amazon.com/cloudformation/index.html) template to create simulator
-	Capture time series data from the simulator into [AWS IoT Core](https://docs.aws.amazon.com/iot/index.html)
-	You will send that data into [Amazon Timestream](https://docs.aws.amazon.com/timestream/index.html) for your visualization


In 2022 the number of connected IoT devise grew to [14.4 billion](https://iot-analytics.com/number-connected-iot-devices/). This number is expected to grow exponentially alongside the jobs in this field. In 2022 global consulting firm McKinsey & Company found the biggest barrier to IoT adoption was skill shortages in the workforce. The number of jobs openings is outpacing the supply of IoT engineers. One of the main barriers to learning about IoT is the cost associated with purchasing IoT hardware. 
