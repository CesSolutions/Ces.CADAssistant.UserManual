# Ces.CatiaAssistant.UserManual
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

<div align="center">
  <img alt="Tools Menu" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/d9f43723-fe69-4df6-a309-7c8366785a8b" />
  <p>Tools Menu</p>
</div>

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

<h1 dir="rtl">Group Items / آیتم های گروه</h1>
<p dir="rtl">
  در این بخش باید برای هر یک از Groupها جزئیات آن را مشخص کنیم. در تصویر زیر مشاهده می کنید که گروه Drawing Types دارای چندین آیتم می باشد. در واقع در زمان تولید کد باید مشخص شود که نوع سند کدام است. برای هر آیتم باید یک کد اختصاری در نظر بگیریم.
</p>

<div align="center">
  <img src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/80727d4e-a4ad-4242-9471-b773951b57e8"/>
  <p>Group Items</p>
</div>

<h1 dir="rtl">Group Item Details / جزئیات آیتم های گروه</h1>
<p dir="rtl">
  برای برخی از آیتم ها می توان جزئیات بیشتری تعریف کرد. در تصویر زیر گروه Types دارای چندین Item می باشد که هر کدام نیز دارای جزئیات بیشتری هستند. برای مثال انواع شیرآلات صنعتی خود دارای گروه بندی بیشتری هستند.
</p>

<div align="center">
  <img alt="Group Item Details" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/41222679-c7a6-461f-9fb5-a7a69cbb3e04"/>
  <p>Group Item Details</p>
</div>

<h1 dir="rtl">Important / مهم</h1>
<p dir="rtl">
  تا اینجا اطلاعات پایه به منظور تولید کد برای قطعات در بانک اطلاعاتی ثبت شده است. نکته مهم در ثبت اطلاعات آنست که برای تمام عنوان هایی که ثبت کردیم باید یک کد منحصر بفرد در نظر بگیریم. در ادامه با چگونگی بکارگیری این داده ها آشنا خواهید شد.
</p>

<h1 dir="rtl">Coding System / سیستم کدگذاری</h1>
<p dir="rtl">
  در این بخش باید سیستم کدگذاری را تعریف کنیم. شما می توانید چندین سیستم تعریف کنید. سیستم پیش فرض Default نامگذاری شده و میتوانید آن را حذف و یا عنوان آن را ویرایش کنید.
</p>

<div align="center">
  <img src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/a614e4ef-9992-48e2-bc61-b6e67690ca51" />
  <p>Coding Systems</p>
</div>

<h1 dir="rtl">Coding System Details / جزئیات سیستم کدگذاری</h1>

<p dir="rtl">
  پس از آنکه سیستم کدگذاری را تعریف کردید می توانید برای هر سیستم جزئیات تولید کد را نیز مشخص کنید. برنامه بصورت خودکار سیستم کذگذاری را انتخاب خواهد کرد که از قبل گزینه IsDefault آن در بخش CodingSystems فعال شده باشد. در ادامه قصد داریم تا سیستمی تعریف کنیم که کد زیر را بتواند تولید کند:
</p>

CES-ASM1244025C06-ASSEMBLY-GATE(PARALLEL DOUBLE-DISC)-REV.3

<div align="center">
  <img alt="Coding System Details" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/964c965a-d586-4ad0-b107-2e557d064819" />
  <p>Coding System Details</p>
</div>

<p dir="rtl">
  تمام آنچه که در تولید نمونه کد بالا مورد نیاز است به تفکیک در بخش Coding System Details تعریف شده است. مورادی که برنامه در زمان تعریف جزئیات بررسی خواهد کرد:
</p>

<ul dir="rtl">
  <li><b>System : </b>
  ازاین بخش باید انتخاب کنیم که جزئیات مورد نظر مربوط به کدام سیستم خواهد یود.
  </li>
  <li><b>Group : </b>
  همانطور که در راهنمای برنامه توضیح داده شد، کد تولید شده می تواند از بخش های مختلفی تشکیل شود که در بخش Groups از منوی Tools توضیح داده شد. هر آیتم از بخش Group فقط چهار بارمی تواند در یک سیستم تعریف شود و بیشتر از آن مجاز نیست که در ادامه توضیح داده خواهد شد.
  </li>
  <li><b>Use Code : </b>
  اگر این گزینه را به ازای هر گروه فعال کنید برنامه در زمان تولید کد از معادل اختصاری آن استفاده خواهد کرد در غیر اینصورت عبارت کامل در نظر گرفته خواهد کرد.
  </li>
  <li><b>Use Detail : </b>
  اگر این گزینه فعال شده باشد برنامه در زمان تولید کد به دنبال جزئیات یک گروه انتخاب شده می گردد. در این شرایط که در ادامه توضیح داده شده است، به محض آنکه کاربر در بخش تولید کد روی یک آیتم کلیک بکند برنامه جزئیات آن گروه را در کنار همان آیتم نمایش خواهد داد تا کاربر بتواند گزینه های بیشتری را انتخاب کند.
  </li>
  <li><b>Fix Value : </b>
  اگر بخواهید یک عبارت ثابت مانند اختصار نام شرکت در ابتدا و هر جای دیگری از کد درج شود می توانید در این قسمت تعریف کنید. همچنین تعریف خط فاصله، پرانتز و... نیز امکانپذیر می باشد. در چنین شرایطی برنامه به گروه انتخاب شده و مقدار Use Code و Use Detail توجه نخواهد کرد و در تولید کد از مقدار تعریف شده استفاده خواهد کرد. در نمونه کد بالا عبارت CES در ابتدای کد و سایر علامت ها مانند - و () ازنوع Fix Value هستند.
  </li>
</ul>

<h1 dir="rtl">Important / مهم</h1>
<p dir = rtl>
  به هر تعداد که لازم داشته باشید می توانید Fix Value تعریف کنید ولی گروه ها تنها چهار بار می توانند در یک سیستم تکرار شوند و بیشتر از آن مجاز نیست.
</p>

<h1 dir="rtl">Code Generator / تولید کننده کد</h1>

<div align="center">
  <img atl="Code Generator" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/4508b8bb-384f-438c-b20f-606cc57edefc" />
</div>

<ul dri="rtl">
  <li><b>System : </b>
  قبل از تولید کد می توانید انتخاب کنید که برنامه مطابق با کدام سیستم اقدام به تولید کد نماید.
  </li>
  <li><b>Code : </b>
  این قسمت مولفه هایی که کد نهایی را تشکیل خواهند داد را نمایش میدهد. مواردی که هنوز انتخاب نشده باشند بین [] قرار میگیرند و یک علامت ؟ نیز در انتها به آن اضافه شده است. مقادیر Fix Value بصورت ثابت و مطابق ترتیب تعریف شده نمایش داده خواهند شد.
  </li>
  <li><b>Refresh : </b>
  با کلیک روی این دکمه اطلاعات سیستم کدگذاری بروزرسانی خواهد شد (اگر داده ها مستقیما از بانک اطلاعاتی ویرایش شوند نیاز است تا این دستور را اجرا کنید).
  </li>
  <li><b>Clear Code : </b>
  کد تولید شده را پاک خواهد کرد و کاربر باید از ابتدا تمامی مولفه ها را انتخاب کند.
  </li>
  <li><b>Apply To Assembly : </b>
  اعمال کد تولید شده روی فایل مونتاژ (فایل باید در حالت انتخاب باشد).
  </li>
  <li><b>Apply To Part : </b>
  اعمال کد تولید شده روی فایل قطعه (فایل باید در حالت انتخاب باشد).
  </li>
  <li><b>Selection Area : </b>
  اگر به این ناحیه دقت کنید خواهید دید که به ترتیب گروه هایی که در بخش Coding System Details برای یک سیستم تعریف کرده بودیم برنامه زبانه هایی با همان نام ایجاد کرده و اطلاعات هر یک از گروه ها را نیز در آن نمایش داده است.
  </li>
</ul>

<h1 dir="rtl">Work with Code generator / کار با تولید کننده کد</h1>
<p dir="rtl">
  چنانچه هر یک از مولفه های کد بصورت [?] نمایش داده شده باشد یعنی آنکه کاربر از این گروه هنوز گزینه ای را انتخاب نکرده است. برای مثال ابتدا به برگه Revision  می رویم و یک شماره نسخه انتخاب میکنیم. نتیجه بصورت زیر خواهد شد:
</p>
<p>
  [Revision?] => Rev.3
  <br/>  
  CES-[DRAWING TYPES?][GROUPS?][PRODUCTION METHODS?][SIZES?][PARTS?][TYPES?]-[DRAWING TYPES?]-[TYPES?]([TYPES?])-REV.3
</p>

<p dir="rtl">
  در این مرحله یک اصلاحیه روی Coding System Details انجام میدهیم و گزینه UseDetail ترتیب شماره 2 را فعال میکنیم. نقشه ها زیر مجموعه ندارند و قصد داریم تا نتیجه این تغیرات را مشاهده کنیم. حال که تغییرات اعمال شد مجددا به Code Generator بروید و از برگه Darwing  Type یک گزینه انتخاب کنید. با توجه به اینکه در سیستم کدگذاری در Orderها شماره  2 و 9 یک گروه تعریف کرده ایم که در شماره 2 به سیستم گفته شده که از مقادیر زیر مجموعه و در شماره 9 گفته شده از خود گروه استفاده شود. نتیجه بصورت زیر خواهد شد:
</p>
<p>
  Order 2 : [Drawing Type?] => [Drawing Type?]
  <br/>
  Order 9 : [Drawing Type?] => Assembly
  <br/>
  CES-[DRAWING TYPES?][GROUPS?][PRODUCTION METHODS?][SIZES?][PARTS?][TYPES?]-ASSEMBLY-[TYPES?]([TYPES?])-REV.3
<p>

<p dir="rtl">
</p>
<p>
<p>

<p dir="rtl">
  اگر با چنین موردی مواجه شدید باید تعریف کد را اصلاح کنید. در ادامه قصد داریم به برگه Types برویم تا نمونه ای از مولفه کدگذاری که دارای زیر مجموعه هست را مشاهده کنیم. در برگه Types گزینه Gate را انتخاب کنید. همانطور که در تصویر زیر مشخص شده به محض انتخاب یک آیتم، لیستی از آیتم های زیر مجموعه در سمت را نمایش داده خواهد شد و متناسب را مقادیر انتخاب شده کد بصورت زیر تولید خواهد شد:
</p>
<p>
  CES-[DRAWING TYPES?][GROUPS?][PRODUCTION METHODS?][SIZES?][PARTS?]C03-ASSEMBLY-GATE(SOLID ONE-PIECE WEDGE)-REV.3
<p>

<div align="center">
  <img alt="Generated Code" src="https://github.com/CesSolutions/Ces.CatiaAssistant.UserManual/assets/74654532/8e64894c-7a9f-4a66-a551-3bc2e17b1e3c" />
<p>Generated Code</p>
</div>

<p dir="rtl">
  در ادامه با انتخاب سایر گزینه ها کد نهایی بصورت زیر تولید خواهد شد:
</p>
<p>
  CES-ASM2105024C01-ASSEMBLY-GATE(BOLTED BONNET)-REV.3
<p>
  
<h1 dir="rtl">Important / مهم</h1>
<p dir="rtl">
  چنانچه پنجره Code Generator را ببندید و مجددا آن را اجرا کنید خواهید دید که کد قبلی مجددا تولید شده است. این ویژگی بدلیل فعال بودن گزینه Remember Previous Selection از بخش Settings می باشد. این ویژگی کمک میکند تا جهت تولید کد بعدی تنهای مولفه های جدید را انتخاب کنید تا کد جدید ایجاد شود و مجبور نباشید تا تمام آیتم ها را مجددا انتخاب کنید.
</p>
