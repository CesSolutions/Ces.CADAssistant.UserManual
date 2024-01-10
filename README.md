# Ces.CADAssistant.UserManual
<p>User manual for guidance in order to use the Ces.CADAssistant desktop application to generate Assembly/Part code.</p>
<p dir="rtl">دستورالعمل کاربر جهت راهنمایی به منظور استفاده از برنامه Ces.CADAssistant جهت تولید کد مونتاژ / قطعه.</p>

<div align="center">
  <div align="center">
    <img width="400" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/9de1fd91-cf04-4592-af1b-7c288a0a66f5"/>  
  </div>
  <div align="center">
    <img width="400" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/6b553ec6-5b93-4e2c-ab4b-b5429ab1fa85"/>  
  </div>
</div>

:-------------------------:|:-------------------------:
  <div align="center">
    <img width="400" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/9de1fd91-cf04-4592-af1b-7c288a0a66f5"/>  
  </div> |    <div align="center">
    <img width="400" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/6b553ec6-5b93-4e2c-ab4b-b5429ab1fa85"/>  
  </div>

<div align="center">
  <img alt="Main Form" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/eed965dc-109b-4cb0-99f1-c4d33bef58f4"/>  
  <p>Main Form</p>
</div>

<p>
  One of the documentation necessary requirements during the design of industrial parts (as well as technical documentation) is to assign a unique code to the parts. This becomes very important when the final product consists of many parts. In such a situation, the code generation should be done based on a procedure so that all engineers and designers can produce standard codes. Some of these codes consist of many elements such as company name, production process, drawing type, part group, size, etc.:
</p>
<p dir="rtl">
  یکی از الزامات اساسی مستندسازی در زمان طراحی قطعات صنعتی (و همچنین مستندات فنی) تخصیص یک کد منحصر بفرد به قطعات است. این مهم زمانی که محصول نهایی از قطعات بسیار زیادی تشکیل شده باشد بسیار اهمیت پیدا خواهد کرد. در چنین شرایطی کدگذاری قطعات می بایست بر مبنای یک دستور العمل انجام گیرد تا تمامی مهندسین و طراحان بتوانند کدهای استانداری تولید کنند. برخی از این کدها از مولفه های زیادی تشکیل می شوند که می تواند مواردی از قبیل نام شرکت، فرآیند تولید، نوع نقشه، گروه قطعه، اندازه و... باشد:
</p>

<div align="center">
  <img width="600" alt="DocumentNumberingSample" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/f8f1138f-aab3-459e-8b4a-e543dcd97a6f">
  <p>Sample Numbering</p>
</div>

<p>
  Generating code many times and in large numbers can be very time-consuming, and there will also be human error. Therefore, the CADAssistant program gives the designer the possibility to define the coding procedure and easily generate many codes and apply them to his parts and assemblies.
</p>

<p dir="rtl">
  تولید کد به دفعات و تعداد زیاد می تواند بسیار وقتگیر باشد ضمن آنکه خطای انسانی نیز وجود خواهد داشت. لذا برنامه CADAssistant این امکان را به طراح می دهد تا ضمن تعریف دستورالعمل مورد نظر، براحتی بتواند کدهای زیاد تولید و روی قطعات و مونتاژهای خود اعمال کند.
</p>

<h1 dir="rtl">Tools Menu / منوی Tools</h1>

<div align="center">
  <img alt="Tools Menu" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/d9f43723-fe69-4df6-a309-7c8366785a8b" />
  <p>Tools Menu</p>
</div>

<ul>
  <li><b>Groups : <b/>
    We call each of the sections shown in the sample image in a rectangular box a "Group", which can be defined in this section. The group can be things like DrawingType, Size, Process, Pressure, Revision,...
  </li>
  <li><b>Group Items : <b/>
    Each group can have subgroups. For example, for DrawingType in the Groups section, you can assign  Mechanical, Electrical, Coating,... as subgroup.
  </li>
  <li><b>Group Item Details : <b/>
    It is possible to define subgroups for "GroupItems" as well. For example, in the Groups section, we should have a title called "Pressure", and in the "GroupItems" section, we should have "Pressure Standards", and in the pressure standards subset, we should have "Pressure Numbers", which is the same as GroupItemDetails.
  </li>
  <li><b>Coding System : <b/>
    A new system can be defined in this section. Let's say you're producing parts for multiple clients, and each of them wants you to follow the different coding procedure Therefore, in this section, you must define as many systems as required. The default system is "Default".
  </li>
  <li><b>Coding system Details : <b/>
    After you have defined the coding system, it is necessary to define the coding details for each systems. Therefore, in this section, you can determine the code generation procedure.
  </li>
  <li><b>Settings : <b/>
    In the settings section, you can create a new database or use an existing database.
  </li>
  <li><b>Refresh : <b/>
    By executing this command, the program settings will be updated.
  </li>
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
    در بخش تنظیمات می توانید بانک اطلاعاتی جدید ایجاد کنید و یا از بانک اطلاعاتی قبلی استفاده کنید.
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
  <img alt="Settings" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/25150af8-f60d-4c11-9da4-f0760b74fbf1"/>
  <p>Settings</p>
</div>

<p>
  در چنین شرایطی گزینه های بخش Coding System غیرفعال می باشد که پس از تعیین بانک اطلاعاتی این گزینه های فعال خواهند شد.
</p>

<h1 dir="rtl">Settings / تنظیمات</h1>
<ul>
  <li><b>Generate Code into Capital Letter : </b>
    If you enable this option, the generated code will be displayed in capital letters, otherwise it will be displayed in the same form as the information you registered in the database.
  </li>
  <li><b>Remember Previous Selection : </b>
  Enabling this option helps the program to save the last generated code and to use generate the next new code, in this case you must select only the item that needs to be changed to generate the new code. It is recommended that this option be active. For example, if your code consists of twenty parts and each time the code is generated, it is only necessary to change the "DrawingType", it is no longer necessary to select all twenty parts again to generate the new code, and it is enough to change the same part.
  </li>
  <li><b>Show Delete Button Next To Items : </b>
  During code generation, the "Delete" option is displayed next to all items so that you can delete that row from the database. It is recommended that this option be disabled unless you are setting up an coding system.
  </li>
  <li><b>Show Edit Button Next To Items : </b>
    During code generation, the "Edit" option is displayed next to all items so that you can edit that row from the database. It is recommended that this option be disabled unless you are setting up an coding system.
  </li>
  <li><b>Select Existing : </b>
  If the database is not recognized in the first run of the application, you can select the previous database to the program.
  </li>
  <li><b>Create New : </b>
  If the database is not recognized in the first run of the application, you can create a new database.
  </li>
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
  <img alt="Delete and Edit Button" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/84f3d817-eda3-4243-aeb7-8dfa32dbdf26"/>
  <p>Showing Delete & Edit button For Each Item in Code Generator</p>
</div>

<h1 dir="rtl">Groups / گروه ها</h1>
<p>
  As you can see in the picture below, the groups are defined at the beginning and these groups will be the elements of the  code. We should consider a abbrevation code for each item.
</p>
<p dir="rtl">
  همانظور که در تصویر زیر مشاهده می کنید در ابتدا گروه ها مشخص شده اند و این گروه ها مولفه های تشکیل دهنده کد قطعه خواهند بود. برای هر آیتم باید یک کد اختصاری در نظر بگیریم.
</p>

<div align="center">
  <img alt="Groups" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/d0f04c9d-0ee3-4ffa-a6c1-d41e7bec324a"/>
  <p>Groups</p>
</div>

<h1 dir="rtl">Group Items / آیتم های گروه</h1>
<p>
  In this section, we have to specify its details for each of the groups. In the picture below, you can see that the "DrawingTypes" group has several items. In fact, at the time of generating the code, it should be determined what type of document it is. We should consider a abbreviation for each item.
</p>
<p dir="rtl">
  در این بخش باید برای هر یک از Groupها جزئیات آن را مشخص کنیم. در تصویر زیر مشاهده می کنید که گروه Drawing Types دارای چندین آیتم می باشد. در واقع در زمان تولید کد باید مشخص شود که نوع سند کدام است. برای هر آیتم باید یک کد اختصاری در نظر بگیریم.
</p>

<div align="center">
  <img src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/80727d4e-a4ad-4242-9471-b773951b57e8"/>
  <p>Group Items</p>
</div>

<h1 dir="rtl">Group Item Details / جزئیات آیتم های گروه</h1>
<p>
  More details can be defined for some items. In the image below, the "Types" group has several items, each of which has more details. For example, "Types" of industrial valves have more groupings.
</p>

<p dir="rtl">
  برای برخی از آیتم ها می توان جزئیات بیشتری تعریف کرد. در تصویر زیر گروه Types دارای چندین Item می باشد که هر کدام نیز دارای جزئیات بیشتری هستند. برای مثال انواع شیرآلات صنعتی خود دارای گروه بندی بیشتری هستند.
</p>

<div align="center">
  <img alt="Group Item Details" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/41222679-c7a6-461f-9fb5-a7a69cbb3e04"/>
  <p>Group Item Details</p>
</div>

<h1 dir="rtl">Important / مهم</h1>
<p>
  So far, the basic information has been registered in the database in order to generate the code for the Assemblies/Parts. The important thing in registering information is that we must assign a unique code for all the titles we registered. In the following, you will learn how to use this data.
</p>
    
<p dir="rtl">
  تا اینجا اطلاعات پایه به منظور تولید کد برای قطعات در بانک اطلاعاتی ثبت شده است. نکته مهم در ثبت اطلاعات آنست که برای تمام عنوان هایی که ثبت کردیم باید یک کد منحصر بفرد در نظر بگیریم. در ادامه با چگونگی بکارگیری این داده ها آشنا خواهید شد.
</p>

<h1 dir="rtl">Coding System / سیستم کدگذاری</h1>
<p>
  In this section, we must define the coding system. You can define multiple systems. The default system is named "Default" and you can delete it or edit its title.
</p>

<p dir="rtl">
  در این بخش باید سیستم کدگذاری را تعریف کنیم. شما می توانید چندین سیستم تعریف کنید. سیستم پیش فرض Default نامگذاری شده و میتوانید آن را حذف و یا عنوان آن را ویرایش کنید.
</p>

<div align="center">
  <img src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/a614e4ef-9992-48e2-bc61-b6e67690ca51" />
  <p>Coding Systems</p>
</div>

<h1 dir="rtl">Coding System Details / جزئیات سیستم کدگذاری</h1>

<p>
  After you define the coding system, you can specify the code generation details for each system. The program will automatically select the coding system whose "IsDefault" option is already enabled in the "CodingSystems" section. Next, we intend to define a system that can generate the following code:
</p>

<p dir="rtl">
  پس از آنکه سیستم کدگذاری را تعریف کردید می توانید برای هر سیستم جزئیات تولید کد را نیز مشخص کنید. برنامه بصورت خودکار سیستم کذگذاری را انتخاب خواهد کرد که از قبل گزینه IsDefault آن در بخش CodingSystems فعال شده باشد. در ادامه قصد داریم تا سیستمی تعریف کنیم که کد زیر را بتواند تولید کند:
</p>

<p>
  CES-ASM1244025C06-ASSEMBLY-GATE(PARALLEL DOUBLE-DISC)-REV.3
</p>

<div align="center">
  <img alt="Coding System Details" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/964c965a-d586-4ad0-b107-2e557d064819" />
  <p>Coding System Details</p>
</div>

<p>
  All that is required in generating the sample code (mentioned above) is defined separately in the "Coding System Details" section. Items that the program will check when defining details:
</p>

<ul>
  <li><b>System : </b>
  From this section, we have to choose which system we nedd to use to generate code.
  </li>
  <li><b>Group : </b>
  As explained in the user manual, the generated code can be composed of different elments as described in the "Groups" section of the "Tools" menu. Each item from the "Group" section can only be defined four times in a system, and more than that is not allowed, which will be explained below.
  </li>
  <li><b>Use Code : </b>
  If you enable this option for each group, the program will use its abbreviated equivalent when generating the code, otherwise, it will consider the full phrase.
  </li>
  <li><b>Use Detail : </b>
  If this option is enabled, the program will look for the details of a selected group when generating the code. In this situation, which is explained below, as soon as the user clicks on an item in the code generation area, the program will display the details of that group next to the same item so that the user can choose more options.
  </li>
  <li><b>Fix Value : </b>
  If you want a fixed expression such as the abbreviation of the company name to be inserted at the beginning and anywhere else in the code, you can define it in this section. It is also possible to define dash, underline , parentheses, etc. In such a situation, the program will not pay attention to the selected group and the value of "Use Code" and "Use Detail" and will use the defined value in generating the code. In the code example above, the word "CES" at the beginning of the code and other symbols such as "-" and "()" are of "Fix Value" type.
  </li>
<ul>

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
  اگر این گزینه فعال شده باشد برنامه در زمان تولید کد به دنبال جزئیات یک گروه انتخاب شده می گردد. در این شرایط که در ادامه توضیح داده شده است، به محض آنکه کاربر در ناحیه تولید کد روی یک آیتم کلیک بکند برنامه جزئیات آن گروه را در کنار همان آیتم نمایش خواهد داد تا کاربر بتواند گزینه های بیشتری را انتخاب کند.
  </li>
  <li><b>Fix Value : </b>
  اگر بخواهید یک عبارت ثابت مانند اختصار نام شرکت در ابتدا و هر جای دیگری از کد درج شود می توانید در این قسمت تعریف کنید. همچنین تعریف خط فاصله، پرانتز و... نیز امکانپذیر می باشد. در چنین شرایطی برنامه به گروه انتخاب شده و مقدار Use Code و Use Detail توجه نخواهد کرد و در تولید کد از مقدار تعریف شده استفاده خواهد کرد. در نمونه کد بالا عبارت CES در ابتدای کد و سایر علامت ها مانند - و () ازنوع Fix Value هستند.
  </li>
</ul>

<h1 dir="rtl">Important / مهم</h1>

<p>
  You can define as many "Fix Values" as you need, but groups can only be repeated four times in a system, and more than that is not allowed.
</p>

<p dir = rtl>
  به هر تعداد که لازم داشته باشید می توانید Fix Value تعریف کنید ولی گروه ها تنها چهار بار می توانند در یک سیستم تکرار شوند و بیشتر از آن مجاز نیست.
</p>

<h1 dir="rtl">Code Generator / تولید کننده کد</h1>

<div align="center">
  <img atl="Code Generator" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/4508b8bb-384f-438c-b20f-606cc57edefc" />
</div>

<ul>
  <li><b>System : </b>
  Before generating the code, you can choose which system the program will use to generate the code.
  </li>
  <li><b>Code : </b>
  This section displays the elements that will form the final code. Items that are not yet selected are placed between "[]" and a "?" is also added at the end. The "Fix Value" values will be displayed in a fixed manner and according to the defined order.
  </li>
  <li><b>Refresh : </b>
  By clicking this button, the information of the coding system will be updated (if the data is edited directly from the database, you need to execute this command).
  </li>
  <li><b>Clear Code : </b>
  It will delete the generated code and the user will have to select all the elements from the beginning.
  </li>
  <li><b>Apply To Assembly : </b>
  Apply the generated code to the assembly file (the file must be active in CAD).
  </li>
  <li><b>Apply To Part : </b>
    Apply the generated code to the part file (the file must be active in CAD).
  </li>
  <li><b>Selection Area : </b>
  If you pay attention to this area, you will see that the program has created tabs with the same name according to the groups that we defined in the "Coding System Details" section for a "system" and displayed the information of each group in it.
  </li>
</ul>

<ul dir="rtl">
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
  اعمال کد تولید شده روی فایل مونتاژ (فایل باید در CAD فعال باشد).
  </li>
  <li><b>Apply To Part : </b>
  اعمال کد تولید شده روی فایل قطعه (فایل باید در CAD فعال باشد).
  </li>
  <li><b>Selection Area : </b>
  اگر به این ناحیه دقت کنید خواهید دید که به ترتیب گروه هایی که در بخش Coding System Details برای یک سیستم تعریف کرده بودیم برنامه زبانه هایی با همان نام ایجاد کرده و اطلاعات هر یک از گروه ها را نیز در آن نمایش داده است.
  </li>
</ul>

<h1 dir="rtl">Work with Code generator / کار با تولید کننده کد</h1>
<p>
  If any of the code elements is displayed as [?], it means that the user has not selected an item from this group yet. For example, we first go to the "Revision" tab and select a revision number. The result will be as follows:
</p>
    
<p dir="rtl">
  چنانچه هر یک از مولفه های کد بصورت [?] نمایش داده شده باشد یعنی آنکه کاربر از این گروه هنوز گزینه ای را انتخاب نکرده است. برای مثال ابتدا به برگه Revision  می رویم و یک شماره نسخه انتخاب میکنیم. نتیجه بصورت زیر خواهد شد:
</p>
<p>
  [Revision?] => Rev.3
  <br/>  
  CES-[DRAWING TYPES?][GROUPS?][PRODUCTION METHODS?][SIZES?][PARTS?][TYPES?]-[DRAWING TYPES?]-[TYPES?]([TYPES?])-REV.3
</p>

<p>
  In this step, we make a correction on "Coding System Details" and activate the "UseDetail" option in order number 2. The "Drawing Types" do not have subsets and we intend to observe the results of these changes. Now that the changes have been applied, go to "Code Generator" again and select an item from "Darwing Type" tab. Considering that we have defined a group in the coding system in Orders No. 2 and 9, in No. 2 the system is told to use the values of the subset and in No. 9 it is said to use the group itself. The result will be as follows:
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

<p>
  If you encounter such a case, you should modify the code definition. Next, we are going to go to the "Types" tab to see an example of a coding component that has a subset. In the "Types" tab, select the "Gate" item as shown in the image below, as soon as an item is selected, a list of sub-set items will be displayed on the right side, and correspondingly the selected values of the code will be generated as follows:
</p>

<p dir="rtl">
  اگر با چنین موردی مواجه شدید باید تعریف کد را اصلاح کنید. در ادامه قصد داریم به برگه Types برویم تا نمونه ای از مولفه کدگذاری که دارای زیر مجموعه هست را مشاهده کنیم. در برگه Types گزینه Gate را انتخاب کنید. همانطور که در تصویر زیر مشخص شده به محض انتخاب یک آیتم، لیستی از آیتم های زیر مجموعه در سمت را نمایش داده خواهد شد و متناسب را مقادیر انتخاب شده کد بصورت زیر تولید خواهد شد:
</p>
<p>
  CES-[DRAWING TYPES?][GROUPS?][PRODUCTION METHODS?][SIZES?][PARTS?]C03-ASSEMBLY-GATE(SOLID ONE-PIECE WEDGE)-REV.3
<p>

<div align="center">
  <img alt="Generated Code" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/8e64894c-7a9f-4a66-a551-3bc2e17b1e3c" />
<p>Generated Code</p>
</div>

<p>
  Then, by choosing other items, the final code will be generated as follows:
</p>

<p dir="rtl">
  در ادامه با انتخاب سایر گزینه ها کد نهایی بصورت زیر تولید خواهد شد:
</p>
<p>
  CES-ASM2105024C01-ASSEMBLY-GATE(BOLTED BONNET)-REV.3
<p>
  
<h1 dir="rtl">Important / مهم</h1>
<p>
  If you close the "Code Generator" window and run it again, you will see that the previous code has been regenerated. This feature is due to the activation of the "Remember Previous Selection" option from the "Settings" section. This feature helps to select only the new elements to generate the next code so that the new code is created and you don't have to select all the items again.
</p>
    
<p dir="rtl">
  چنانچه پنجره Code Generator را ببندید و مجددا آن را اجرا کنید خواهید دید که کد قبلی مجددا تولید شده است. این ویژگی بدلیل فعال بودن گزینه Remember Previous Selection از بخش Settings می باشد. این ویژگی کمک میکند تا جهت تولید کد بعدی تنهای مولفه های جدید را انتخاب کنید تا کد جدید ایجاد شود و مجبور نباشید تا تمام آیتم ها را مجددا انتخاب کنید.
</p>

<h1 dir="rtl">Minimal Mode / حالت کمینه</h1>
<p>
  Having the "CADAssistant" program open may take up screen space and prevent the designer from working. Therefore, choosing "Minimal Mode" will help to make more space available to the designer and the program will be displayed with a small icon on the right-bottom side of the screen. If you click on the icon, the "Code Generator" window will be launched, and if you right-click, the main page of the program will be launched.
</p>

<p dir="rtl">
  باز بودن برنامه CADAssistant ممکن است فضای صفحه نمایش را اشغال کند و مانع کار کردن طراح شود. بنابراین انتخاب Minimal Mode کمک خواهد کرد تا فضای بیشتری در دسترس طراح باشد و برنامه با یک آیکن کوچک در سمت راست-پایین صفحه نمایش نمایش داده خواهد شد. اگر روی آیکن کلیک کنید پنجره Code Generator اجرا خواهد شد و اگر راست کلیک کنید صفحه اصلی برنامه اجرا خواهد شد.
</p>

<div align="center">
  <img alt="Minimal Mode" src="https://github.com/CesSolutions/Ces.CADAssistant.UserManual/assets/74654532/13a4baa0-d219-464d-b582-b17bf211678b">
  <p>Minimal Mode</p>
</div>
