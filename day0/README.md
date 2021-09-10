<div dir="rtl">
<p>در این دوره و با اجرای این تمرین میخواهیم مراحل کشف بوزون هیگز را که منجر به جایزه ی نوبل سال ۲۰۱۲ شد مرور کنیم. آزمایش CMS در <a href="https://cds.cern.ch/record/1471016?ln=en" target="_blank">مقاله ی مشهور خود در آن سال</a> نمودار زیر را به عنوان نشانه ای از وجود بوزون هیگز منتشر کرد</p>
  <img src="https://ars.els-cdn.com/content/image/1-s2.0-S0370269312008581-gr004_lrg.jpg" style="width:50%" />
  <p>
    ما تصمیم داریم با بازتولید مرحله به مرحله ی این نمودار اجزاء آن و نحوه ی نتیجه گیری از آن را یاد بگیریم.
  </p>
  
<p>در ادامه این صفحه قصد داریم در مورد آماده کردن محیط کاری برای اجرای آن در سه سطح مختلف صحبت کنیم. لطفا قبل از انجام هر کاری دستورالعمل را تا انتها مطالعه کنید.</p>
<h1>نصب و راه&zwnj;اندازی (پیشرفته)</h1>
<p>این تمرین را به راحتی می&zwnj;توانید رو کامپیوتر خود اجرا کنید. به شرطی که سیستم عامل لینوکس را روی دستگاه خود داشته باشید.</p>
<p>در قدم اول باید دستورالعمل زیر را انجام دهید تا برنامه های لازم را برای خود نصب نمائید. بعد از آن می&zwnj;توانید تمرین های روزهای دیگر را به راحتی انجام دهید.</p>
<h2>برنامه های مورد نیاز</h2>
<ol>
<li>
<h3>رووت&zwnj; (ROOT)</h3>
<p>این یکی از اصلی ترین برنامه هایی است که توسط سرن توسعه پیدا کرده و در تمام آزمایش&zwnj;های آن کاربرد دارد. اگر یکی از نسخه های به&zwnj;روز سیستم عاملهای<code> <a href="https://snapcraft.io/install/root-framework/ubuntu">Ubuntu</a>, <a href="https://snapcraft.io/install/root-framework/mint">Mint</a>, <a href="https://snapcraft.io/install/root-framework/debian">Debian</a>, <a href="https://snapcraft.io/install/root-framework/fedora">Fedora</a>, <a href="https://snapcraft.io/install/root-framework/opensuse">OpenSUSE</a>, <a href="https://snapcraft.io/install/root-framework/centos">CentOS</a>, <a href="https://snapcraft.io/install/root-framework/arch">Arch</a></code> را داشته باشید می&zwnj;توانید از دستور زیر برای نصب این برنامه استفاده کنید</p>
<p style="text-align: left;"><code>sudo snap install root-framework</code></p>
<p>با این دستور (و وارد کردن کلمه ی عبور خواسته شده) برنامه&zwnj;ی رووت دانلود شده و در دستگاه شما نصب می&zwnj;گردد. برای کسب اطلاعات بیشتر در مورد این پکیج میتوانید به <a href="https://root.cern/blog/snap-announcement/">این صفحه</a> مراجعه کنید.</p>
<p>برای تست کردن اینکه این برنامه به خوبی نصب شده، کافی است دستور <code>root</code> را در ترمینال اجرا کنید. باید محیط کاری این برنامه باز شده باشد. با زدن دستور <code>.q</code> میتوان از این محیط خارج شد.</p>
</li>
<li>
<h3>اجرای محیط ژوپیتر</h3>
<p>اگر چه برنامه ی رووت به زبان <span style="text-align: left;"> c++ </span> نوشته شده، اما به راحتی می&zwnj;توان از طریق پایتون به کتابخانه های آن دسترسی پیدا کرد.</p>
<p>برای باز کردن یک فایل پایتون که قابلیت کار با رووت را از طریق پایتون داشته باشید کافی است دستور زیر را اجرا کنید</p>
<code style="text-align: left;">root --notebook</code>
<p>این دستور باید یک صفحه ی مرورگر را باز کند تا بتوانید در آن کد پایتون خود را اجرا کنید.</p>
</li>
<li>
<h3>در صورت بروز مشکل</h3>
<ul>
<li>
<h3>پایتون</h3>
<p>ممکن است یکی از مشکلات عدم نصب پایتون در سیستم باشد. برای نصب پایتون اگر از <code> <a href="https://snapcraft.io/install/root-framework/ubuntu">Ubuntu</a></code>&nbsp; استفاده می&zwnj;کنید از دستور زیر استفاده کنید:</p>
<p style="text-align: left;"><code>
      sudo apt install python
    </code></p>
</li>
<li>
<h3>ژوپیتر</h3>
<p style="text-align: left;"><code>
        sudo pip3 install --upgrade pip
      </code> <br /><code>
        sudo pip3 install jupyter
      </code></p>
</li>
</ul>
</li>
</ol>
<h1>شرکت کنندگان در مدرسه ی سه روزه ی سرن</h1>
<p>اگر شما در <a href="https://indico.cern.ch/e/iut1400" target="_blank">مدرسه ی آشنائی با فعالیت های سرن</a> پذیرفته شده&zwnj;اید، و دستورالعمل بالا به هر دلیلی برای شما اجرا نشد، نباید نگران باشید.</p>
<p>در اولین جلسه ی کارگاه عملی به شما یک شناسه ی کاربری داده میشود تا بتوانید از سیستم محاسباتی اماده شده برای این تمرین استفاده کنید.</p>
<h1>کاربران حرفه ای ویندوز</h1>
<p>متاسفانه نصب و راه اندازی برنامه ی رووت در ویندوز همراه با کمی پیچیدگی می&zwnj;باشد. میتوانید دستورالعمل آن را در این سایت مشاهده کنید.</p>
<a href="https://root.cern/releases/release-62406/#windows">سایت اصلی نصب رووت</a></div>
