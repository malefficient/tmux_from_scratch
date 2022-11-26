# tmux_from_scratch
For the past 3-4 years I've periodically gone through my .tmux config to try and minimize changes whenever more sane defaults made their way upstream.

No more! 

I realized that my .tmux config files from 3-4 years back were _way_ more self-descriptive. So now, I'm taking a page from https://ianthehenry.com/posts/how-to-configure-tmux/
Johnnys self-descriptive tmux from scratch repo

'''
 tmux -f /dev/null list-keys | wc -l *255*
 tmux -f ./tmux.conf list-keys  | wc -l 
'''
