# AdMovie_O
xcFrameWork로 변경 O

## <a name="heading1"></a> 1. 영화 광고 요청하기

<h5 class="tab-title" data-tab-name="banner-load">Swift</h5>

``` swift
import UIKit
import AdMovie_O

class MyViewController: UIViewController {

   var movieView: AdMovieView?

    override func viewDidLoad() {
        super.viewDidLoad()
        movieView = AdMovieView(token: "Input Your Token")
        bannerAdView.loadAd()
    }

}
```
