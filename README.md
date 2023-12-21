# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

为您提供 CS , DS , 商科 编程作业代写

<img src="design2023866.jpg"  width="200" />


Task-1:
interactive-resume.js
In this Mini-Project, you will enhance the website you created in MP2 by adding interactive 
features to it using JavaScript.
Having an online-resume, especially for CS-majors, would be very important. Instead of 
handing a paper resume or attaching a PDF to an email, you could just share a link or a barcode with 
recruiters, hr, or hiring managers.
An online resume would be an ideal place for you to showcase your achievements, like the 
projects you have worked on, or initiatives you have been involved with. Unfortunately, an online 
resume could also be a vulnerability. You may not want just anyone to be able to access your info on 
the internet, or you may want a recruiter from one company see something that another recruiter from 
another company should not see.
By providing username and passwords to recruiters, you can control or shape their experience
when they visit your website.
• In WebStorm navigate to cs392 >> projects >> mini-projects >> mp2 >> and 
copy/paste everything to the cs392 >> projects >> mini-projects >> mp3 folder. On
mp3, right click, select “New” and then “JavaScript File”.
• Name the new file something unique but similar to “interactive-resume.js”.
• Hardcode a set of predefined username/passwords in a JavaScript hash-map where 
the passwords are the keys (must be unique), and the usernames are the values.
Ex:
const userPass = {
 "122-taymaz": "tazman",
 "1212-sandman": "sandy"
};
Note:
Handling authentication in frontend is not safe and not recommended
even with data-hiding techniques, our hardcoded username/passwords
would be found, but for now we will use interactive-resume.js to 
store our hash-map. We will learn SSR (server-side-rendering) once 
we reach the React section of our class. With SSR, we can manage 
increase the security of our applications by rendering sensitive info 
from the back-end.
• All internal webpages and your website’s Home page must be connected to the 
interactive-resume.js using the <script></script> tag. 
o The <header></header>:
1. All internal webpages, including the Home page, regardless of size 
specified in the media-queries, must have a login button in the
<header></header> section, on the right corner of the screen.
2. When the button is pushed a Log-in screen will become visible in the 
<main></main> section, on top of other contents, (use z-index). 
3. If the same button is clicked again the Log-in screen should disappear
again, (using a Boolean condition you can keep toggling back and forth).
o The <nav></nav>:
1. The link of at least 2 internal webpages must be hidden by default. In the 
above examples, I have hidden “References” and the “Documents”.
2. Use display: none; to hide the links you want to hide, but make sure the 
appearance of your navigation menu, regardless of size or orientation
specified in the media-queries, remains proportional to the screen. You 
can achieve this by using flex-box.
Ex:
o The <main></main>:
1. Using the Log-in screen, users are authenticated.
2. If a user’s attempts to log-in more than 3 times, using window.close(); the 
browser window must be closed.
3. If a user’s attempts to log-in is less than 3 times, for each failed attempt, 
the user must be notified as to how many more attempts there are.
4. On the last attempt (the 3rd attempt) user must be notified that the 3rd
attempt would be the last attempt. If the user fails, the Log-in screen
should disappear.
5. The notifications must be presented to the user dynamically
Note:
You may NOT use: alert() or .alert, .print(), .write(), .log(), any addons, or libraries.
6. You must construct an empty <div></div> with a textual child tag (p,
h1…h6) in the <main></main> and dynamically add/change its contents
using .innerHTML.
Ex:
HTML
JS
7. Your notification div, must become visible only when the user fails to 
login successfully, otherwise it should remain hidden. Also, if user 
succeeds after an attempt, it should disappear again. Use z-index for the 
notification div as well, so that it opens on top of other contents in 
<main></main>.
8. Upon successful login, the hidden internal webpages will become visible,
the Log-in screen and the notification div invisible.
Note:
1. Make good use of margins and paddings. Leave open spaces and do not clutter.
2. Use calc( + ) for font-sizes.
3. Chose a background color for your main tags (header, nav, main, footer), but maintain a 
sense of uniformity.
4. Test your page for contrast errors using http://wave.webaim.org/, if you were exceeding 
10 errors, consider choosing a different theme. This website could be helpful: 
https://colorhunt.co/
5. Use customized fonts, like google fonts.
6. Use Flex-box with Media Queries. 
• After you are done, open BU’s Server, from Tools >> Deployment >> Browse Remote Host.
• Where it says <None>, to its right there is an arrow, click on it and select BU’s Server.
• Drag your mp3 file and folders from the left-panel and drop it into the same folder cs392 >> 
projects >> mini-projects >> mp3, on the right-panel.
• Check your work before you go to the next task.
• Go to cs-people.bu.edu/YOUR-KERBEROS-USERNAME/cs392/projects/miniprojects/mp3/ YOUR_NEW_RESUME.HTML; if you ended up looking at your resume with 
its new interactive features, then you have successfully finished Task-1, otherwise retrace your 
steps or seek help (from the instructor or the graders).
Task-2:
Assignment Submission:
• Navigate to Blackboard >> Mini-Project-3 >> Create Submission
• Paste this link in the text filed:
cs-people.bu.edu/YOUR-KERBEROS-USERNAME/cs392/projects/miniprojects/mp3/ YOUR_NEW_RESUME.HTML
• You Link might be slightly different from the one above, so make sure that it opens to 
your assignment before you submit it. Add comments if you like, and click submit.

## 作业代写价格:

|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$60-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式

微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
