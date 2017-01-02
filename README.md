I used [Jekyll Now](https://github.com/barryclark/jekyll-now) to start my first Jekyll site on github.

I recommend [the tutorial by Barry Clark](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/).

I had a very difficult time installing the necessary gems for Github. First, I installed homebrew. After that, I followed the instructions on [this reddit page](https://www.reddit.com/r/Jekyll/comments/542vvh/macos_sierra_broke_jekyll/). I installed ruby 2.3.3, which was the last stable release before 2.4.0. It seems that github requires json 1.8 which would not compile with ruby 2.4.0. However, it compiled find with ruby 2.3.3.
