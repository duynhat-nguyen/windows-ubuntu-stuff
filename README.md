# windows-ubuntu-stuff
This is to note my modifications to Windows and Ubuntu when using them

### 6:53 Feb 12, 2020
Changing Linux to use local time. 
I did change Windows to use UTC. However, I sign in my Google account on Chrome both Ubuntu and Windows and my Google Account keep "pending". 
https://help.ubuntu.com/community/UbuntuTime#Multiple_Boot_Systems_Time_Conflicts

### 14:51 Feb 27, 2020
Download YouTube Videos in terminal using youtube-dl command
https://itsfoss.com/download-youtube-linux/

### 20:51 Feb 29, 2020
Scale all *.png images in a folder to 1270x720  
```bash
!for f in *.png; do ffmpeg -i "$f" -vf scale=1280:720 "./xxx/${f%%.png}.png"; done  
```
https://superuser.com/questions/839751/resize-more-than-one-image-using-ffmpeg

Programming stuff
This is to note the answer of some question that I faced.  
What is %matplotlib inline?


Đối với mảng 2 chiều, axis = 0 là cộng từ trên xuống, axis = 1 là cộng từ trái qua.  

Không softmax cho int được

np.random.randn(1, 148) < 0.5 (week6/testCases.py of Deep learning by Andrew Coursera)  

Do not use batchnorm as the regularization, "use it as a way to normalize your hidden units activation and therefore speed up learning" (10:48 - 10:53 Why does Batch Norm work? Week 3 Improving Deep Neural Networks: Hyperparameter https://www.coursera.org/specializations/deep-learning)  

I still don't know why tf.nn.sigmoid_cross_entropy_with_logits in TF2 will sum logits, the deprecated one in TF1 does not but the one which will replace it tf.nn.sigmoid_cross_entropy_with_logits_v2 in TF1 does sum.  

X_train = X_train_flatten/255. -> What does the little period mean? (TensorFlow_Tutorial_v3b_tf2.ipynb Week 7 https://www.coursera.org/specializations/deep-learning)  

tf.set_random_seed(1)                             # to keep consistent results
seed = 3 (2 dòng này có nghĩa là gì) (TensorFlow_Tutorial_v3b_tf2.ipynb Week 7 https://www.coursera.org/specializations/deep-learning)  

https://stackoverflow.com/questions/5130968/how-can-i-copy-the-output-of-a-command-directly-into-my-clipboard  

lxc  

VSCode, Evolution, Edge (Dark Reader, GoFullPage, Lastpass, Video speed controller, Vimium, Weava), RTI, ROS, Stretchly, Tweaks, OBS, DB Browser,  , CommuniTheme Icon suru, Scaling factor 1.2, Uninstall Games + Thunderbird,  

In order to switch between windows of an app, press Alt + "`"

https://tipsonubuntu.com/2019/08/01/drawing-basic-image-editor-similar-microsoft-paint/
