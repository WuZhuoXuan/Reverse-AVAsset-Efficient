**Description:**

Reverse and output a video file keeping the same compression, format, and frame rate as the source video.

**Usage:**

```
#import "AVUtilities.h"

AVAsset *originalAsset = [[AVURLAsset alloc] initWithURL:[NSURL urlWithString:@"~/video.mp4"]];
AVAsset *reversedAsset = [AVUtilities assetByReversingAsset:originalAsset outputURL:[NSURL urlWithString:@"~/reversedvideo.mp4"]];
```

**Result:**

![alt tag](http://i.imgur.com/SmdiGL3.gif)
![alt tag](http://i.imgur.com/Xl8pjnl.gif)
