
<div dir="rtl">  
    <p><h2>تغییر state به شکل immutable</h2></p>  
    <p><h4>کدهای این درس ادامه درس react-017-lists است</h4></p>
    <p><h4>Key یک property خاص است که هنگام کار با لیست ها باید نوشته شود. React انسان نیست بنابراین نمی تواند ببیند شما کدام فرد از افراد (لیست) را حذف کرده اید. کد ما در حال حاضر کار می کند اما مسئله اینجاست که react چیزی به نام virtual DOM دارد. در این virtual DOM نسخه ای از DOM آینده (که با متد render نمایش داده می شود) را نگه می دارد تا با DOM فعلی مقایسه کند و هر قسمتی از DOM جدید که با قبلی متفاوت باشد، آن قسمت دوباره render می شود. مشکل اینجاست که در لیست ها باید چیزی مثل یک id وجود داشته باشد که به React اجازه دهد هر کدام افراد را به صورت خاص شناسایی کند تا به جای render کردن دوباره ی کل افراد در لیست، فقط افرادی را دوباره render کند که تغییر کرده اند.
          </h4></p>
    <p><h4>شناسایی این افراد با استفاده از key در ری اکت انجام می شود که باید یک مقدار منحصر به فرد و یکتا باشد. در حالت عادی، افراد از پایگاه داده دریافت می شوند و id مخصوص خودشان را دارند. ما می توانیم همان id را برابر با key آن ها قرار دهیم. در کد ما از پایگاه داده استفاده نمی شود بنابراین باید به صورت دستی مقدار خاصی برایشان تعیین کنیم:
           </h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
</div>  
<br /><br /><br /><br />  
  
<p>This project was bootstrapped with <a href="https://github.com/facebookincubator/create-react-app">Create React App</a></p>