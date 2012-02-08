Read Me
=====================

**WSChart's target is using simple code to create charts.**

PieChart's screenshots as below:

'pieChart.showIndicator = YES'

![showIndicator style](http://wwww.flickr.com/photos/pyanfield/6810927299/ "showIndicator style")

'pieChart.openEnabled = YES'

![showIndicator style](http://wwww.flickr.com/photos/pyanfield/6810927259/ "showIndicator style")

I hope you can use this project to create Pie Chart, Bar Chart, Scatter Chart, Line Chart, Comno Chart, Column Chart, Area Chart and Candlestick Chart.

Usage
------------------

You can use the pie chart like this:

	NSMutableDictionary *pieData = [[NSMutableDictionary alloc] init];
    NSMutableArray *colors = [[NSMutableArray alloc] init];
    pieData = [NSMutableDictionary dictionaryWithObjectsAndKeys:[[NSNumber alloc] initWithFloat:20],@"test1",[[NSNumber alloc] initWithFloat:34],@"test2",[[NSNumber alloc] initWithFloat:55],@"test3",[[NSNumber alloc] initWithFloat:12],@"test4",[[NSNumber alloc] initWithFloat:78],@"test5",[[NSNumber alloc] initWithFloat:110],@"test6",nil];
    colors = [[NSMutableArray alloc] initWithObjects:[UIColor purpleColor],[UIColor blueColor],[UIColor greenColor],[UIColor redColor],[UIColor yellowColor],[UIColor brownColor], nil]; 
    
    WSPieChartView *pieChart = [[WSPieChartView alloc] initWithFrame:CGRectMake(10.0, 10.0, 500.0, 500.0)];
    pieChart.data = pieData;
    pieChart.colors = colors;
    pieChart.touchEnabled = YES;
    pieChart.showIndicator = YES;            //pieChart.openEnabled = YES;
    [self.view addSubview:pieChart];


Adding WSChart to your project
------------------

#### First : Add "charts" folder to your project.

#### Second : Add QuartzCore framework to your project.

TODO List
----------------------- 
* PieChart : ongoing
* Column Chart : next one.

License
------------------------
WSChart follows MIT license.

Except when otherwise stated (look for LICENSE files in directories or
information at the beginning of each file) all software and
documentation in WSChart project is licensed as follows: 

	Copyright (C) 2012, pyanfield  - pyanfield@gmail.com

	Permission is hereby granted, free of charge, to any person obtaining a copy of
	this software and associated documentation files (the "Software"), to deal in
	the Software without restriction, including without limitation the rights to
	use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
	of the Software, and to permit persons to whom the Software is furnished to do
	so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.

Other
------------------------
You can contact me with mail 'pyanfield at gmail.com'.
if you use SinaWeibo, you can follow @pyanfield.



