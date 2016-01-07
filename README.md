# WLCircleProgressView
自定义环形进度条

示例代码:

    WLCircleProgressView *circleProgress1 = [WLCircleProgressView viewWithFrame:CGRectMake(80, 80, 100, 100)
                                                               circlesSize:CGRectMake(30, 5, 30, 5)];
    circleProgress1.layer.cornerRadius = 10;
    circleProgress1.progressValue = 0.2;
    [self.view addSubview:circleProgress1];
    self.progressView1 = circleProgress1;
