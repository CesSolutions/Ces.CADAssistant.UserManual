# Ces.CatiaAssistant.UserManual (Preparing... / در حال آماده سازی)
<p>User manual to guide CATIA designer to use Ces.CatiaAssistant desktop application for code generation for parts.</p>
<p dir="rtl">دستورالعمل کاربر جهت راهنمایی به منظور استفاده از برنامه Ces.CatiaAssistant جهت تولید کد قطعه.</p>

<div align="center">
  <img alt="Main Form" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/eed965dc-109b-4cb0-99f1-c4d33bef58f4"/>  
  <p>Main Form</p>
</div>

<p dir="rtl">
  یکی از الزامات اساسی مستندسازی در زمان طراحی قطعات صنعتی (و همچنین مستندات فنی) تخصیص یک کد منحصر بفرد به قطعات است. این مهم زمانی که محصول نهایی از قطعات بسیار زیادی تشکیل شده باشد بسیار اهمیت پیدا خواهد کرد. در چنین شرایطی کدگذاری قطعات می بایست بر مبنای یک دستور العمل انجام گیرد تا تمامی مهندسین و طراحان بتوانند کدهای استانداری تولید کنند. برخی از این کدها از مولفه های زیادی تشکیل می شوند که می تواند مواردی از قبیل نام شرکت، فرآیند تولید، نوع نقشه، گروه قطعه، اندازه و... باشد:
</p>

<div align="center">
  <img width="600" alt="DocumentNumberingSample" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/f8f1138f-aab3-459e-8b4a-e543dcd97a6f">
  <p>Sample Numbering</p>
</div>

<p dir="rtl">
  تولید کد به دفعات و تعداد زیاد می تواند بسیار وقتگیر باشد ضمن آنکه خطای انسانی نیز وجود خواهد داشت. لذا برنامه CatiaAssistant این امکان را به طراح می دهد تا ضمن تعریف دستورالعمل مورد نظر، براحتی بتواند کدهای زیاد تولید و روی قطعات و مونتاژهای خود اعمال کند.
</p>

<h1 dir="rtl">Tools Menu / منوی Tools</h1>
<ul>
  <li><b>Groups : <b/></li>
  <li><b>Group Items : <b/></li>
  <li><b>Group Item Details : <b/></li>
  <li><b>Coding System : <b/></li>
  <li><b>Coding system Details : <b/></li>
  <li><b>Settings : <b/></li>
  <li><b>Refresh : <b/></li>
</ul>

<ul dir="rtl">
  <li><b>Groups : <b/>
    به هر یک از بخش هایی که در تصویر نمونه در کادر مستطیلی نشان داده شده یک گروه می گوییم که میتوان در این بخش آنها را تعریف کرد. گروه می تواند مواردی از قبیل DrawingType, Size, Process, Pressure, Revision,... باشد.
  </li>
  <li><b>Group Items : <b/>
    هر گروه می تواند زیر مجموعه داشته باشد. برای مثال در نمونه DrawingType در بخش Groups می تواند مواردی از قبل Mechanical, Electrical, Coating,... را در نظر گرفت.
  </li>
  <li><b>Group Item Details : <b/>
    این امکان وجود دارد تا برای GroupItemها نیز زیر مجموعه تعریف کرد. برای مثال در بخش Groups یک عنوان با نام Pressure داشته باشیم و در بخش GroupItems استانداردهای فشار و در زیر مجموعه استانداردهای فشار اعداد فشار را داشته باشیم که همان GroupItemDetails می باشد.
  </li>
  <li><b>Coding System : <b/>
    در این بخش می توان یک سیستم جدید تعریف کرد. فرض کنید در حال تولید قطعه برای چندین کارفرما هستید و هر یک از آنها از شما می خواهند که از یک دستورالعمل کدگذاری پیروی کنید. بنابراین در این بخش باید به تعداد مورد نیاز یک سیستم تعریف کنید. سیستم پیش فرض Default می باشد.
  </li>
  <li><b>Coding system Details : <b/>
    پس از آنکه سیستم کدگذاری را تعریف کردید ضروریست تا به ازای هر یک از سیستم ها جزئیات کدگذاری را تعریف کنید. بنابراین در این بخش می توانید شیوه تولید کد را تعیین کنید.
  </li>
  <li><b>Settings : <b/>
    در بخش تنظیمات میتوانید بانک اطلاعاتی جدید ایجاد کنید و یا از بانک اطلاعاتی قبلی استفاده کنید.
  </li>
  <li><b>Refresh : <b/>
    با اجرای این دستور تنظیمات برنامه بروزرسانی خواهد شد.
  </li>
</ul>

<h1 dir="rtl">First Execution / اولین اجرای برنامه</h1>
<p>
  پس از اولین اجرای برنامه چنانچه بانک اطلاعاتی پیدا نشود برنامه پنجره Settings را باز خواهد کرد و شما باید تعیین کنید که برنامه یک بانک اطلاعاتی جدید ایجاد کند و یا اینکه از بانک اطلاعاتی قبلی استفاده کند.
</p>

<div align="center">
  <img alt="Settings" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/25150af8-f60d-4c11-9da4-f0760b74fbf1"/>
  <p>Settings</p>
</div>

<p>
  در چنین شرایطی گزینه های بخش Coding System غیرفعال می باشد که پس از تعیین بانک اطلاعاتی این گزینه های فعال خواهند شد.
</p>

<h1 dir="rtl">Settings / تنظیمات</h1>
<ul>
  <li><b>Generate Code into Capital Letter : </b></li>
  <li><b>Remember Previous Selection : </b></li>
  <li><b>Show Delete Button Next To Items : </b></li>
  <li><b>Show Edit Button Next To Items : </b></li>
  <li><b>Select Existing : </b></li>
  <li><b>Create New : </b></li>
</ul>

<ul dir="rtl">
  <li><b>Generate Code into Capital Letter : </b>
  اگر این گزینه را فعال کنید، کد تولید شده بصورت حروف بزرگ نمایش داده خواهد شد در غیراینصورت به همان شکلی که اطلاعات در بانک اطلاعاتی ثبت کرده اید نمایش داده خواهد شد.
  </li>
  <li><b>Remember Previous Selection : </b>
  فعال بودن این گزینه کمک می کند که برنامه آخرین کد تولید شده را ذخیره کرده و جهت تولید کد جدید فقط آن آیتمی که باید تغییر کند را انتخاب کنید تا کد تولید شود. پیشنهاد می گردد این گزینه فعال باشد. برای مثال اگر کد شما از بیست قسمت تشکیل شده باشد و در هر بار تولید کد فقط لازم باشد تا نوع نقشه تغییر کند دیگر ضروری نیست که تمام بیست قسمت را مجددا انتخاب کنید تا کد تولید شود و تنها کافیست که همان قسمت را تغییر دهید.
  </li>
  <li><b>Show Delete Button Next To Items : </b>
  در زمان تولید کد گزینه حذف در کنار تمام آیتم ها نمایش داده می شود تا بتوانید آن ردیف را از بانک اطلاعاتی حذف کنید. پیشنهاد می گردد این گزینه غیرفعال باشد مگر آنکه در حال تنظیم سیستم کدگذاری هستید.
  </li>
  <li><b>Show Edit Button Next To Items : </b>
  در زمان تولید کد گزینه ویرایش در کنار تمام آیتم ها نمایش داده می شود تا بتوانید آن ردیف را از بانک اطلاعاتی ویرایش کنید. پیشنهاد می گردد این گزینه غیرفعال باشد مگر آنکه در حال تنظیم سیستم کدگذاری هستید.
  </li>
  <li><b>Select Existing : </b>
  در صورتی که در اولین اجرای برنامه بانک اطلاعاتی شناسایی نشد می توانید بانک اطلاعاتی قبلی را به برنامه معرفی کنید.
  </li>
  <li><b>Create New : </b>
  در صورتی که در اولین اجرای برنامه بانک اطلاعاتی شناسایی نشد می توانید بانک اطلاعاتی جدید ایجاد کنید.
  </li>
</ul>

<div align="center">
  <img alt="Delete and Edit Button" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/84f3d817-eda3-4243-aeb7-8dfa32dbdf26"/>
  <p>Showing Delete & Edit button For Each Item in Code Generator</p>
</div>

<h1 dir="rtl">Groups / گروه ها</h1>
<p dir="rtl">
  همانظور که در تصویر زیر مشاهده می کنید در ابتدا گروه ها مشخص شده اند و این گروه ها مولفه های تشکیل دهنده کد قطعه خواهند بود. برای هر آیتم باید یک کد اختصاری در نظر بگیریم.
</p>

<div align="center">
  <img alt="Groups" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/d0f04c9d-0ee3-4ffa-a6c1-d41e7bec324a"/>
  <p>Groups</p>
</div>

<h1 dir="rtl">GroupItems / آیتم های گروه</h1>
<p dir="rtl">
  در این بخش باید برای هر یک از Groupها جزئیات آن را مشخص کنیم. در تصویر زیر مشاهده می کنید که گروه Drawing Types دارای چندین آیتم می باشد. در واقع در زمان تولید کد باید مشخص شود که نوع سند کدام است. برای هر آیتم باید یک کد اختصاری در نظر بگیریم.
</p>

<div align="center">
  <img src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/80727d4e-a4ad-4242-9471-b773951b57e8"/>
  <p>Group Items</p>
</div>

<h1 dir="rtl">GroupItemDetails / جزئیات آیتم های گروه</h1>
<p dir="rtl">
  برای برخی از آیتم ها می توان جزئیات بیشتری تعریف کرد. در تصویر زیر گروه Types دارای چندین Item می باشد که هر کدام نیز دارای جزئیات بیشتری هستند. برای مثال انواع شیرآلات صنعتی خود دارای گروه بندی بیشتری هستند.
</p>

<div align="center">
  <img alt="Group Item Details" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/79619b97-4b2f-4811-90b7-217159956d65"/>
</div>
