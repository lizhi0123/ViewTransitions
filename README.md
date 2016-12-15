# ViewTransitions
![效果图](https://github.com/lizhi0123/ViewTransitions/blob/master/animation.gif)

核心代码
 [UIView transitionFromView:fromView
                        toView:toView
                      duration:1.0
                       options:options
                    completion:^(BOOL finished) {
                        // animation completed
                        if (priorConstraints != nil)
                        {
                            [self.view removeConstraints:priorConstraints];
                        }
                    }];
