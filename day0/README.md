<div dir="rtl">
<h1>نصب و راه&zwnj;اندازی (پیشرفته)</h1>
<p>این تمرین را به راحتی می&zwnj;توانید رو کامپیوتر خود اجرا کنید. به شرطی که سیستم عامل لینوکس را روی دستگاه خود داشته باشید.</p>
<p>در قدم اول باید دستورالعمل زیر را انجام دهید تا برنامه های لازم را برای خود نصب نمائید. بعد از آن می&zwnj;توانید تمرین های روزهای دیگر را به راحتی انجام دهید.</p>
<h2>برنامه های مورد نیاز</h2>
<ol>
<li>
<h3>رووت&zwnj; (ROOT)</h3>
<p>این یکی از اصلی ترین برنامه هایی است که توسط سرن توسعه پیدا کرده و در تمام آزمایش&zwnj;های آن کاربرد دارد. اگر یکی از نسخه های به&zwnj;روز سیستم عاملهای<code> <a href="https://snapcraft.io/install/root-framework/ubuntu">Ubuntu</a>, <a href="https://snapcraft.io/install/root-framework/mint">Mint</a>, <a href="https://snapcraft.io/install/root-framework/debian">Debian</a>, <a href="https://snapcraft.io/install/root-framework/fedora">Fedora</a>, <a href="https://snapcraft.io/install/root-framework/opensuse">OpenSUSE</a>, <a href="https://snapcraft.io/install/root-framework/centos">CentOS</a>, <a href="https://snapcraft.io/install/root-framework/arch">Arch</a></code> را داشته باشید می&zwnj;توانید از دستور زیر برای نصب این برنامه استفاده کنید</p>
<p style="text-align: left;"><code>sudo snap install root-framework</code></p>
<p>با این دستور (و وارد کردن کلمه ی عبور خواسته شده) برنامه&zwnj;ی رووت دانلود شده و در دستگاه شما نصب می&zwnj;گردد</p>
<p>برای تست کردن اینکه این برنامه به خوبی نصب شده، کافی است دستور <code>root</code> را در ترمینال اجرا کنید. باید محیط کاری این برنامه باز شده باشد. با زدن دستور <code>.q</code> میتوان از این محیط خارج شد.</p>
</li>
<li>
<h3>پایتون</h3>
<p>اگر چه برنامه ی رووت به زبان <span style="text-align: left;"> c++ </span> نوشته شده، اما به راحتی می&zwnj;توان از طریق پایتون به کتابخانه های آن دسترسی پیدا کرد. برای این کار لازم است پایتون روی دستگاه شما نصب باشد. برای نصب پایتون اگر از <code> <a href="https://snapcraft.io/install/root-framework/ubuntu">Ubuntu</a></code>&nbsp; استفاده می&zwnj;کنید از دستور زیر استفاده کنید:</p>
<p style="text-align: left;"><code>
      sudo apt install python
    </code></p>
</li>
  <li>
    <h3>
      ژوپیتر
    </h3>
    <p style="text-align: left;">
      <code>
        sudo pip3 install --upgrade pip
      </code>
      <br/>
      <code>
        sudo pip3 install jupyter
      </code>
    </p>
  </li>
</ol>
</div>
