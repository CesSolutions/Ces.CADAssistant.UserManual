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
