> http://apprendre-python.com/

#تعلّم لغة بايثون للبرمجة:
**بايثون** هي **لغة برمجة** من اللغات الأكثر أهمية حاليا. لغة سهلة  التعلم، تستعمل كثيرا كأمثلة خلال تدريس البرمجة. ستجد في هذه السلسلة من الدروس القواعد الأساسية لفهم هذه اللغة.

[صورة1]

## ما هي لغة البايثون؟
**البايثون** هي **لغة برمجة** إخترعها **غويدو فان روسوم** حيث كانت أول إصدارة عام 1991. البايثون **لغة مؤوّلة** (interpreted) فليس من الضروري التصريف (compilation) قبل التنفيذ (execution). إن كانت لك تجربة مع البرمجة، ستحس أن للبايثون لمسة شِعرية.  المبرمجين غالبا ما يستمتعون في إيجاد الطريقة الأبسط والأكثر فعالية في كتابة مجموعة من التعليمات (instructions). قليلون من قاموا بإنتقاد منطق كتابة البايثون على عكس الجافاسكريبت مثلا.

## ماذا تصنع بالبايثون؟
البايثون لغة بسيطة وفعالة في نفس الوقت. تسمح بكتابة سكريبتات جدّ بسيطة لكن بفضل  مكتباته المتنوّعة ، يمكنك العمل على مشاريع ذات طموح أسمى. 

- **الويب**: حاليا البايثون مع إطار العمل جانغو (Django Framework) يمثلان خيارا تقنيا ممتازا لإنجاز مشاريع مواقع إنترنت كبيرة.
- **النظام**: يعرف البايثون أيضا بإستعماله من طرف مديري الأنظمة لأجل إنشاء مهام تكرارية أو مهام صيانة.

إضافة إلى ذلك،  إن أردت إنشاء تطبيقات جافا باستعمال البايثون فيمكنك ذلك عن طريق المشروع جايثون Jython.

## لماذا تفضيل البايثون على لغات أخرى؟
بايثون هي لغة سهلة التعلم ذات شفرة سهلة القراءة ما يجعل إتقانها أسهل. أحيانا تكون أوجز بخمس مرات مقارنة بلغة الجافا مثلا، ما يزيد من إنتاجية المطوّر ويقلّل تلقائيا عدد العلل (bugs).
بايثون يستعمل أيضا في المجالات العلمية ، المعلوماتية الحيوية كمثال. عدّة  مكتبات متوفّرة لهذا المجال كالوحدة (module):  
[biopython](http://biopython.org/DIST/docs/tutorial/Tutorial.html). كذلك، توجد مكتبات تسهّل إنشاء ألعاب الفيديو ثنائية الأبعاد (وثلاثية الأبعاد) مثل: [pyGame](http://www.pygame.org/).

## من يستعمل البايثون؟
كلّ من غوغل (غويدو فان روسوم عمل لصالح غوغل من عام 2005 حتى عام 2012)، ياهوو، مايكروسوفت، نازا صرحوا باستعمالهم البايثون وهذاعلى سبيل المثال لا الحصر.

# ثبّت البايثون على حاسوبك
## التثبيت على لينوكس أو ماك
إن كنت تعمل في بيئة **لينوكس** أو **ماك**، فأنت محظوظ: البايثون مثبّت مع النظام.

[صورة2]

## التثبيت على وينداوز
إن كنت تعمل على نظام **وينداوز**، فغيّر نظام تشغيلك...
شخصيا أفضل العمل على **يوبانتو** الذي يقوي إحساسك كمطور بالتناغم مع جهازك و إضافة إلى هذا كل شيء مجاني. كذلك، ستحتاج كثيرا نقلك عملك على خادوم يعمل بنظام لينوكس. ليكن في علمك أنه حاليا أكثر المشاريع تستضاف على خوادم لينوكس  مقارنة على الخوادم بتراخيص غير حرة.

إن أردت إبقاء الوينداوز -  مع كل جهودي لإقناعك بدخول العالم الحر - يمكنك تحميل ملف التثبيت من هذا [الرابط] (https://www.python.org/download/) .

## أي إصدار تختار؟
قم بإختيار أحدث إصدار مستقر مع الإشارة إلى أن الإصدار 2.7 هو الإصدار اﻷكثر إستعمالا حاليا. هناك مشاكل توافق بين الإصدار 2 و الإصدار 3 للبايثون. أنصح بتعلم بايثون 2 ثم تعلّم الفروق مع بايثون 3 ليكن في مقدورك حل مشاكل الإنتقال بين الإصدارين.

# مؤوّل البايثون (Python Interpreter)
لاستعمال البايثون على يوبانتو كمثال، شغّل الطرفية (terminal):
[صورة]
ثم نفّذ الأمر `python`: 
[صورة]
لاحظ الرموز `<<<` التي تعني أن مؤوّل البايثون مستعد لاستقبال تعليمات. بصفة عامة، إذا رأيت هاته الرموز في صفحة من صفحات هذه الدورة التعليمية، فهذا يعني أنه عليك تنفيذ تلك الشفرة المعروضة في مؤوّل البايثون. 
بإمكانك القيام بعملية جمع بسيطة كما يلي:
[صورة]

هو ذا! الآن لديك فكرة عن مؤوّل البايثون.

في بعض المحررات - WingIDE مثلا - مؤوّل البايثون يكون مدمجا.

# محرّرات البايثون (IDE)
## المحرر WingIDE
المحرر WingIDE هو أحد أفضل المحررات للمبتدئين بنسخته المجانية. تم تطويره من طرف مطوّري بايثون لمطوّري بايثون  من أجل تعليم بايثون. النسخة المجانية تحتوي بالتأكيد على مزايا أقل من النسخة الكاملة. يمكن تحميل النسخة المجانية من [الرابط](https://wingware.com/). 

إذا كنت تعمل على يوبانتو ، قم بتحميل الحزمة `.deb` ، نقرتين على الملف ثم أنقر على  **تثبيت**.  إذا صادفتك مشاكل  في الاعتماديات (dependencies)، قم بتنفيذ الأمر التالي في الطرفية: 

    sudo apt-get install -f

هذه معاينة للبرمجية:
[صورة]

## المحرر Sublime Text
أما هذا فهو محرّري المفضّل: خفيف، جميل، وقوي! 
[صورة]
المحرّر Sublime Text يحوي مجموعة من الإضافات سرعان ما تدمن عليها! نسخته القاعدية مجانية مع تنبيه صغير يظهر من حين لآخر ليطلب منك إن كنت تريد شراء ترخيص لدعم المشروع لكن لا شيء يجبرك على فعل ذلك.

فكّر في تثبيت [packagecontrol](https://packagecontrol.io/installation) الذي يسمح لك بتثبيت الأدوات اللازمة لمشروعك.

إليك قائمة صغيرة للإختصارات الأكثر استعمالا:

|     الإختصار     	|                 العملية                	|
|:----------------:	|:--------------------------------------:	|
|     Ctrl + X     	|                                حذف سطر 	|
|     Ctrl + P     	|                يسمح بالإبحار في أي ملف 	|
|     Ctrl + R     	|    نقل المؤشر نحو دالة في الملف الحالي 	|
|     Ctrl + L     	|                     تحديد السطر الحالي 	|
|     Ctrl + D     	|             تحديد الكلمة الحالية كاملة 	|
| Ctrl + Shift + D 	|                    مضاعفة السطر الحالي 	|
|     Ctrl + M     	| تحريك المؤشر نحو النهاية الأخرى للدالة 	|
|     Ctrl + G     	|         نقل المؤشر نحو سطر س  من الملف 	|
| Ctrl + Shift + T 	|                    فتح آخر ملف تمّ غلقه 	|
| CTRL + SHIFT + F 	|   القيام بعملية البحث في ملفات مجلد ما 	|
|  CTRL + ALT + P  	|                          تبديل المشروع 	|

# المحرّر VIM
المحرّر `vim ` هو محرّر  يعمل على الطرفية أكثر غنى من `nano`.
    sudo aptitude install vim

عند تحرير ملف بـ `vim` تكون بدءا في وضع الأوامر الذي يسمح لك بمعالجة الملف. في الحقيقة، لست في وضع يمكنك من الكتابة  مباشرة لكن يمكنك manipuler البيانات. مثلا الزر `w` ينقلك إلى الكلمة التالية  ولا يقوم بكتابة حرف `w`. سيكون هذا مزعجا في البداية. للدخول في وضع تحرير النص، عليك النقر على الزر `i`.

إليك قائمة للعمليات الأكثر استعمالا في وضع الأوامر  في `vim`:

|   الأمر  |             العملية             |
|:--------:|:-------------------------------:|
|     i    |           تبديل إلى وضع الإدخال |
|    :q!   |                  الخروج دون حفظ |
|    :qw   |                 الحفظ ثم الخروج |
|    :w    |                       حفظ الملف |
|    d$    |      حذف البيانات حتى آخر السطر |
|    dw    | حذف البيانات حتى الكلمة التالية |
|    de    |              حذف الكلمة الحالية |
|     w    |     الإنتقال إلى الكلمة التالية |
|    2w    |        القفز إلى الأمام بكلمتين |
|    2dw   |                  حذف آخر كلمتين |
|     0    |            الذهاب إلى أول السطر |
|     u    |                 إلغاء آخر عملية |
|    yy    |                       نسخ السطر |
|    4yy   |                      نسخ 4 أسطر |
|     p    |                         لصق بعد |
|     P    |                         لصق قبل |
| Ctrl + R |       التراجع عن الإلغاء الأخير |
| Ctrl + Z |                             غلق |
|     /    |                             بحث |
|     ?    |           بحث في الإتجاه العكسي |
|     n    |            => Occurence التالية |


# الحساب والمتغيرات في بايثون
## الحساب
واحدة من أول مزايا المؤوّل هي القيام بالحسابات:

    >>> 1+2
    3

بإمكانك إضافة فراغات دون أي incidence:

    >>> 1 + 2
    3

كل العمليات قابلة للاستعمال:

    >>> 1-10
    -9
    >>> 2*10
    20
    >>> 100/4
    25
    >>> 10%4
    2
    >>> 2**3
    8

نجمة مضاعفة تمثل الأس.

يوجد مع ذلك خطأ -يجب تجنبه- في إصدارات البايثون الأقل من بايثون 3:

    >>> 10/3
    3

مفاجأة 10/3 = 3 . إذن، لم هذا الخطأ؟ البايثون يفكر بالأعداد الصحيحة لأننا قدّمنا له عددين صحيحين. لإيجاد نتيجة عشرية، عليك إستعمال هذه الكتابة:

    >>> 10.0/3
    3.3333333333333335
    >>> 10/3.0
    3.3333333333333335

## المتغيرات
المتغير (variable)  هو علبة ظاهرية حيث يمكننا وضع قيمة (أو عدّة قيم) معطاة. الفكرة هي تخزين مؤقت للقيمة المعطاة للعمل بها. بالنسبة لجهازك المتغير هو عنوان يؤشر على مكان في الذاكرة الحية حيث تخزّن المعلومات المرتبطة بها.

نعطي قيمة ما لمتغير `age` ثم نقوم بعرض قيمته بعد ذلك:

    >>> age = 30
    >>> age
    30
ثم نضيف 10 إلى قيمة هذا المتغير:

    >>> age = 30
    >>> age = age + 10
    >>> age
    40

بإمكاننا وضع متغيّر في متغيّر آخر:

    >>> age = 30
    >>> age2 = age
    >>> age2
    30

بإمكانك تقريبا وضع كل ما تريد في متغيّرك بما فيها النصوص:

    >>> age = "I've 30 years"
    >>> age
    "I've 30 years"

يمكنك القيام بوصل (concatenation) ، أي بمعنى إضافة نص إلى نص:
    >>> age = age + " and I'm still young!"
    >>> age
    "I've 30 years and I'm still young!"

بإمكانك حتى  ضرب سلسلة محارف:

    >>> age = "young"
    >>> age * 3
    'youngyoungyoung'

Clearly, إذا جربت القيام بعمليات جمع بين المتغيّرات التي هي أعداد مع أخرى نصوص، المؤوّل سيقوم ب groner ك:

    >>> age = "I've 30 years"
    >>> age
    "I've 30 years"
    >>> age + 1
    Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
    TypeError: cannot concatenate 'str' and 'int' objects

تلاحظ لطف المؤوّل  فهو يقول لك ما لا يجوز لك فعله: لا تقم بوصل `str`و `int`.

## ترشيح علامة الإقتباس 
كيف تدمج مِحرف الإقتباس مع أنه يؤشّر إلى بداية المعطيات ونهاية المعطيات؟

    >>> text = "Hi I'm \"Olivier\""
    >>> text
    Hi I'm "Olivier"

أو

    >>> text = 'Hi I\'m "Olivier"'
    >>> text
    'Hi I\'m "Olivier"'

توجد طريقة أخرى لتخزين النص في متغيّر : إستعمال ثلاثية من علامة الإقتباس. هذه الأخيرة تسمح بعدم ترشيح علامات الإقتباس في المعطيات:

    >>> text = """
    ... Hi I'm "olivier"
    ... """
    >>> text
    '\nHi I\'m "olivier"\n'

## تسمية متغير

لا يمكنك تسمية المتغيرات بالسهولة التي تظن على النحو الذي تراه مناسبا لوجود كلمات مستعملة أصلا في البايثون. إليك قائمة الكلمات المحجوزة:

    print in and or if del for is raise assert elif from lambda return break else global not try class except while continue exec import pass yield def finally

لماذا تمّ حجز هذه الكلمات؟  لأنها تستعمل لشيء آخر، سنعرف عن هذا بالتفاصيل في الدروس القادمة. 

لتسمية متغيّر عليك استعمال الحروف الأبجدية اللاتينية (بايثون 3 يقبل الحروف العربية)، الأرقام ورمز الكشيدة `_`. لا تستعمل رموز التنقيط أو الرمز `@`. لا يجب وضع الأرقام في أول اسم المتغير:

    >>> 1var = 1
    File "<stdin>", line 1
        1var = 1
        ^
    SyntaxError: invalid syntax

كما تلاحظ، البايثون لا يسمح بهذا النوع من  الصياغة لكنه يسمح ب `var1 = 1`.

## أنواع المتغيرات
نوع المتغيرات في البايثون، بمعنى إضافة إلى القيمة ، أي متغير بطاقة تشير إلى ماهية القيمة في هذه العلبة الظاهرية.

إليك قائمة أنواع المتغيرات:


**عدد صحيح (integer)**: للإشارة إلى عدد صحيح دون فاصلة عشُرية.
**الفاصلة العائمة (float)**: مثال : `1.5`.
**سلسلة محارف (string)**: للتبسيط هي كل ما ليس عددا.

هناك الكثير من الأنواع الأخرى لكن ربما من المبكر التكلم عنها الآن.

لمعرفة نوع متغير ما، يمكنك استعمال الدالة `type()`:

    >>> v = 15
    >>> type(v)
    <type 'int'>
    >>> v = "Olivier"
    >>> type(v)
    <type 'str'>
    >>> v = 3.2
    >>> type(v)
    <type 'float'>

# لوائح البايثون
اللائحة (`list` / `array`) في البايثون هي متغير يمكننا أن نضع فيه عدة متغيرات.

## إنشاء لائحة
يمكن إنشاء لائحة ببساطة:

    >>> l = []

يمكن رؤية محتوى اللائحة بمناداتها كما يلي:

    >>> l
    []

## إضافة قيمة إلى لائحة
يمكنك إضافة القيم التي تريدها خلال عملية إنشاء اللائحة:

    >>> l = [1,2,3]
    >>> l
    [1, 2, 3]

أو  إضافتها بعد الإنشاء عن طريق `append` التي تعني "أضف" في الإنجليزية:

    >>> l = []
    >>> l
    []
    >>> l.append(1)
    >>> l
    [1]
    >>> l.append("ok")
    >>> l
    [1, 'ok']

   نرى أنه من الممكن خلط متغيرات من أنواع مختلفة في نفس اللائحة. يمكن أيضا وضع لائحة داخل لائحة.

## عرض عنصر من اللائحة
للقراءة من القائمة، يمكنك طلب عرض عرض قيمة الفهرس (index) الذي يهمك:

    >>> l = ["a","d","m"]
    >>> l[0]
    'a'
    >>> l[2]
    'm'

يبدأ العنصر الأول دائما بالفهرس 0. من أجل قراءة العنصر الأول نستعمل القيمة `0` ، للعنصر الثاني نستعمل القيمة `1`،إلخ.

كذلك من الممكن تغيير القيمة باستعمال فهرسها 

    >>> l = ["a","d","m"]
    >>> l[0]
    'a'
    >>> l[2]
    'm'
    >>> l[2] = "z"
    >>> l
    ['a', 'd', 'z']

## حذف عنصر باستعمال الفهرس

أحيانا يكون عليك حذف عنصر من اللائحة. لفعل هذا يمكنك استعمال الدالة `del`.

    >>> l = ["a", "b", "c"]
    >>> del l[1]
    >>> l
    ['a', 'c']

## حذف عنصر باستعمال قيمته
من الممكن حذف عنصر من لائحة باستعمال قيمته بالطريقة `remove`.

    >>> l = ["a", "b", "c"]
    >>> l.remove("a")
    >>> l
    ['b', 'c']

## عكس قيم لائحة
من الممكن عكس عناصر لائحة بالطريقة `reverse`.

    >>> l = ["a", "b", "c"]
    >>> l.reverse()
    >>> l
    ['c', 'b', 'a']

## حساب عدد عناصر لائحة
من الممكن حساب عدد عناصر لائحة بالدالة `len`.

    >>> l = [1,2,3,5,10]
    >>> len(l)
    5

## حساب عدد مرات ورود قيمة ما

لمعرفة عدد مرات الورود لقيمة معينة في لائحة، يمكنك استعمال الطريقة `count`.

    >>> l = ["a","a","a","b","c","c"]
    >>> l.count("a")
    3
    >>> l.count("c")
    2

## إيجاد فهرس قيمة  ما
تسمح الطريقة `index` بمعرفة موضع العنصر المبحوث عنه.

    >>> l = ["a","a","a","b","c","c"]
    >>> l.index("b")
    3

## التعامل مع لائحة
إليك بعض الأفكار في التعامل مع اللوائح:

    >>> l = [1, 10, 100, 250, 500]
    >>> l[0]
    1
    >>> l[-1] # آخر عنصر
    500
    >>> l[-4:] # أخر 4 عناصر
    [500, 250, 100, 10]
    >>> l[:] # كل العناصر
    [1, 10, 100, 250, 500]
    >>> l[2:4] = [69, 70]
    [1, 10, 69, 70, 500]
    >>> l[:] = [] # تفريغ اللائحة
    []
    
## العبور عبر قيم لائحة
لعرض كل قيم لائحة، يمكن استعمال حلقة تكرار (loop):

    >>> l = ["a","d","m"]
    >>> for letter in l:
    ...     print letter
    ... 
    a
    d
    m

استعمل الدالة `enumerate` إن أردت استرجاع قيمة الفهرس أيضا.


    >>> for letter in enumerate(l):
    ...     print letter
    ... 
    (0, 'a')
    (1, 'd')
    (2, 'm')

القيم المسترجعة عبر حلقة التكرار هي على  شكل متتابعات (tuples).

## نسخ قائمة

الكثير من المبتدئين يرتكبون خطأ نسخ لائحة بالطريقة التالية:

    >>> x = [1,2,3]
    >>> y = x

وإن كنت تريد تغيير قيمة من اللائحة `y`، القائمة `x` ستتأثّر بهذا التغيير:


    >>> x = [1,2,3]
    >>> y = x
    >>> y[0] = 4
    >>> x
    [4, 2, 3]

بهذه الطريقة، أنت فقط تعمل على نفس اللائحة فقط تمّ تسميتها باسمين مختلفين. إذن ماذا تعمل  لنسخ لائحة بطريقة تضمن استقلالها؟

    >>> x = [1,2,3]
    >>> y = x[:]
    >>> y[0] = 9
    >>> x
    [1, 2, 3]
    >>> y
    [9, 2, 3]

للمعطيات الأكثر تعقيدا، استعمل الدالة `deepcopy` من الوحدة `copy`

    >>> import copy
    >>> x = [[1,2], 2]
    >>> y = copy.deepcopy(x)
    >>> y[1] = [1,2,3]
    >>> x
    [[1, 2], 2]
    >>> y
    [[1, 2], [1, 2, 3]]

## تحويل سلسلة محارف إلى لائحة

أحيانا قد تحتاج إلى تحويل سلسلة محارف إلى لائحة. الدالة `split` تمكّنك من ذلك.

    >>> my_string = "Olivier:ENGEL:Strasbourg"
    >>> my_string.split(":")
    ['Olivier', 'ENGEL', 'Strasbourg']
## تحويل لائحة إلى سلسلة محارف

العكس ممكن بالدالة `join`. 

    >>> l = ["Olivier","ENGEL","Strasbourg"]
    >>> ":".join(l)
    'Olivier:ENGEL:Strasbourg'

## إيجاد عنصر في لائحة
لمعرفة عنصر في لائحة، يمكنك استعمال الكلمة المفتاحية `in` بالطريقة التالية:

    >>> l = [1,2,3,5,10]
    >>> 3 in l
    True
    >>> 11 in l
    False

## الدالة `range`

الدالة `range` تقوم بتوليد لائحة مكوّنة من متتالية حسابية بسيطة.

    >>> range(10)
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

## توسيع لائحة بلائحة أخرى

لضم لائحتين يمكنك استعمال الدالة `extend`:


    >>> x = [1, 2, 3, 4]
    >>> y = [4, 5, 1, 0]
    >>> x.extend(y)
    >>> print x
    [1, 2, 3, 4, 4, 5, 1, 0]

## تلميحات
عرض العنصرين الأولين من لائحة:

    >>> l = [1,2,3,4,5]
    >>> l[:2]
    [1, 2]
عرض العنصر الأخير من لائحة:

    >>> l = [1, 2, 3, 4, 5, 6]
    >>> l[-1]
    6
عرض العنصر الثالث عدّا من النهاية:

    >>> l = [1, 2, 3, 4, 5, 6]
    >>> l[-3]
    4
عرض الثلاث عناصر الأخيرة:

    >>> l = [1, 2, 3, 4, 5, 6]
    >>> l[-3:]
    [4, 5, 6]
يمكن جمع لائحتين لوصلهما باستعمال العملية `+` :

    >>> x = [1, 2, 3]
    >>> y = [4, 5, 6]
    >>> x + y
    [1, 2, 3, 4, 5, 6]

بإمكانك حتى ضرب لائحة لمضاعفتها:

    >>> x = [1, 2]
    >>> x*5
    [1, 2, 1, 2, 1, 2, 1, 2, 1, 2]

ما قد يفيدك في إعطاء القيم المبدئية:

    >>> [0] * 5
    [0, 0, 0, 0, 0]

# متتابعات البايثون 

المتتابعة هي لائحة لا يمكن تغييرها.

## إنشاء متتابعة
لإنشاء متتابعة، يمكنك استعمال الكتابة التالية:

    >>> my_tuple = ()
## إضافة قيمة إلى متتابعة
لإنشاء متتابعة بقيم معطاة، يمكنك فعل ذلك بالشكل التالي:

    >>> my_tuple = (1, "ok", "olivier")
القوسان ليستا أساسيتان لكنهما يسهّلنا مقروئية الشفرة (للتذكير، قوة البايثون تكمن في سهولة القراءة):

    >>> my_tuple = 1, 2, 3
    >>> type(my_tuple)
    <type 'tuple'>

عند إنشاء متتابعة بقيمة وحيدة، لا تنس إضافة فاصلة فدونها لن تكون متتابعة.

    >>> my_tuple = ("ok")
    >>> type(my_tuple)
    <type 'str'>
    >>> my_tuple = ("ok",)
    >>> type(my_tuple)
    <type 'tuple'>

## عرض قيمة متتابعة
المتتابعة هي شكل من أشكال اللوائح، لهذا يمكن قراءة المعطيات فيها بنفس الطريقة:

    >>> my_tuple[0]
    1
وطبعا إن جرّبنا تغيير قيمة فهرس ما، فالمفسّر  سيرد بخطأ لأن لا يمكن تغيير قيم المتتابعة بعد الإنشاء:

    >>> my_tuple[1] = "ok"
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    TypeError: 'tuple' object does not support item assignment
    
## ما فائدة المتتابعة إذن؟
المتتابعة تسمح بالإسناد (assignment) المتعدد:

    >>> v1, v2 = 11, 22
    >>> v1
    11
    >>> v2
    22

كما تسمح بإرسال عدة قيم حين إستدعاء دالة ما:

    >>> def give_me_your_name():
    ...     return ("olivier", "engel")
    ... 
    >>> give_me_your_name()
    ('olivier', 'engel')

تستعمل المتتابعة إيضا في تعريف الثوابت التي لا نحتاج لتغييرها بعد الإنشاء.


# قواميس البايثون

القاموس في البايثون هو شكل من اللوائح ولكنه بدل استعمال فهرس كقيمة عددية يستعمل مفاتيح، قيم أخرى إضافة للعددية.



## إنشاء قاموس
لإنشاء قاموس نستعمل الكتابة التالية:

    >>> a = {}
## كيفية إضافة قيم
لإضافة قيمة إلى قانوس، عليك تحديد المفتاح إضافة إلى القيمة:

    >>> a = {}
    >>> a["last_name"] = "engel"
    >>> a["first_name"] = "olivier"
    >>> a
    {'last_name': 'engel', 'first_name': 'olivier'}

يمكنك استعمال مفاتيح عددية كما في اللوائح.


## إسترجاع قيمة

الطريقة (method) `get` تمكنك من استرجاع قيمة موجودة في قاموس مع إرجاع قيمة افتراضية إن كان مفتاحها غير موجودا:

    >>> data = {"first_name": "Olivier", "age": 30}
    >>> data.get("first_name")
    'Olivier'
    >>> data.get("address", "Unknown")
    'Unknown'

## التحقق من وجود مفتاح
يمكنك استعمال الطريقة `has_key` للتحقق عن مفتاح تبحث عنه:

    >>> a.has_key("last_name")
    True

## حذف عنصر
يمكن حذف عنصر بتحديد مفتاحه كما بالنسبة للوائح:

    >>> del a["last_name"]
    >>> a
    {'first_name': 'olivier'}

## إسترجاع المفاتيح عن طريق حلقة تكرار

لاسترجاع المفاتيح نستعمل الطريقة `keys`:

    >>> f = {"last_name":"engel","first_name":"olivier"}
    >>> for key in f.keys():
    ...     print key
    ... 
    last_name
    first_name

## إسترجاع القيم عن طريق حلقة تكرار
لهذه نستعمل الطريقة `values`:

    >>> f = {"last_name":"engel","first_name":"olivier"}
    >>> for val in f.values():
    ...     print val
    ... 
    engel
    olivier
## إسترجاع المفاتيح والقيم معا عن طريق حلقة تكرار
لاسترجاع المفاتيح والقيم معا في نفس الوقت، نستعمل الطريقة `items` التي تُرجِع متتابعة:

    >>> f = {"last_name":"engel","first_name":"olivier"}
    >>> for key, val in f.items():
    ...     print key, val
    ... 
    last_name engel
    first_name olivier

## استعمال المتتابعات كمفاتيح

من نقاط قوة البايثون الدمج بين استعمال المتتابعات والقواميس  كما في حالة استعمال الإحداثيات

    >>> b = {}
    >>> b[(3,2)]=12
    >>> b[(4,5)]=13
    >>> b
    {(4, 5): 13, (3, 2): 12}

## إنشاء نسخة مستقلة من قاموس
لا يمكن نسخ قاموس عن طريق `dict1 = dict2`:

    >>> d = {"k1":"olivier", "k2":"engel"}
    >>> e = d
    >>> d["k1"] = "XXX"
    >>> e
    {'k2': 'engel', 'k1': 'XXX'}

لإنشاء نسخة مستقلة، يمكن استعمال الطريقة `copy`:

    >>> d = {"k1":"olivier", "k2":"engel"}
    >>> e = d.copy()
    >>> d["k1"] = "XXX"
    >>> e
    {'k2': 'engel', 'k1': 'olivier'}

# دوال البايثون
دالة البايتون (function)  هي عبارة عن مجموعة أوامر متتالية يمكننا مناداتها باسم. 

## إنشاء دالتي الأولى
نقوم بإنشاء دالة ترجِع العمر:

    >>> def my_age():
    ...     return 30;
    ... 
    >>> my_age()
    30

عليك أن لا تنسخ وتلصق هذا المثال، أكتبه بيدك سطرا سطرا وأنقر على زر Enter للرجوع إلى السطر في كل مرة. علامات `<` الثلاثة وكذلك النقط الثلاثة معروضة من طرف المؤول.

بادئ ذي بدء، لإعلام المؤول بأنك تريد إنشاء دالة، تستعمل الكلمة المفاتحية `def` متبوعة باسم وأقواس ثم بنقطتين `:`.

نلاحظ أيضا وجود  مسافة فارغة بين الثلاث نقاط `...` والكلمة المفتاحية `return`، وهي تمثّل المسافة البادئة وهي لا تحسّن فقط الكتابة بل تؤشر إلى أننا مازلنا داخل الدالة.  لإضافة المسافة البادئة إضغط على  المفتاح `TAB` في لوحة المفاتيح أو أنقر على مفتاح المسافة 4 مرّات. 

## العوامل (Parameters)
نقوم بإنشاء دالة أخرى
    >>> def increment_me(a):
    ...     return increment_me + 2
    ... 
    >>> increment_me(1)
    3

هذه الدالة تقوم بإضافة 2 للقيمة المدخلة كعامل. يمكن استعمال عدة عوامل:

    >>> def increment_me(a, b):
    ...     return 30 + a + b
    ... 
    >>> increment_me(1, 2)
    33

إن فهمت مبادئ عمل الدوال، تكون قد فهمت 80% من البرمجة.

## عامل أساسي

عندما تضع للدالة عوامل فإن هذه العوامل إجبارية و نسيانها يؤدي إلى خطأ .

    >>> def increment_me(a, b):
    ...     return 30 + a + b
    ...
    >>> increment_me(1)
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    TypeError: increment_me() takes exactly 2 arguments (1 given)

## عملية Splat
العملية Splat  تستعمل كثيرا

    def my_function(*var)
    def my_function(**var)
    my_function(*var)
    my_function(**var)

## لائحة عوامل
بالإمكان استرجاع القيم المدخلة عن طريق لائحة:

    >>> def increment_me(*param):
    ...     return param[0] + param[1] + param[2]
    ... 
    >>> increment_me(1, 2, 3)
    6
    >>> increment_me(10, 20, 30)
    60

## Rendre obligatoire uniquement certains paramètres avec une liste
Si vous désirez rendre obligatoire uniquement certains paramètres, vous pouvez utiliser la syntaxe suivante:

    >>> def ma_fiche(prenom, nom, *reste):
    ...     return prenom + " " + nom 
    ... 
    >>> ma_fiche("olivier","engel")
    'olivier engel'
On remarque que le paramètres "reste" est précédé d'une étoile *.
## Utiliser un dictionnaire pour les paramètres
Vous pouvez utiliser un dictionnaire en paramètres pour cela vous devez ajouter une double étoile: **

    >>> def ma_fiche(**parametres):
    ...     return parametres["prenom"]
    ...
    >>> ma_fiche(prenom="olivier")
    'olivier'
## Utilisation de splat liste au niveau des appels de fonctions
Reprennons l'exemple de la fonction augmente_moi:

    >>> def augmente_moi(*param):
    ...     return param[0] + param[1] + param[2]
    ... 
Nous avons vu qu'il était possible de faire ceci:

    >>> augmente_moi(1, 2, 3)
    6
L'utilisation de l'étoile permet de passer par une liste:

    >>> data = [1, 2, 3]
    >>> augmente_moi(*data)
    6
## Utilisation de splat dictionnaire au niveau des appels de fonctions
Prénons l'exemple de cette fonction:

    >>> def test(firstname="", lastname=""):
    ...     return "{} {}" .format(firstname, lastname)
Créons notre dictionnaire:

    >>> data = {'firstname':'olivier',     'lastname':'engel'}
Et envoyons notre variable avec une étoile *

    >>> test(*data)
    'lastname firstname'
Puis avec deux étoiles **

    >>> test(**data)
    'olivier engel'
## Portée des variables (variable globale et variable locale)
Une variable déclarée à la racine d'un module est visible dans tout ce module. On parle alors de variable globale.

    >>> x = "hello"
    >>> def test():
    ...     print x
    ... 
    >>> test()
    hello
Et une variable déclarée dans une fonction ne sera visible que dans cette fonction. On parle alors de variable locale.

    >>> x = False
    >>> def test():
    ...     x = "hello"
    ... 
    >>> test()
    >>> x
    False
## Procédure et fonctions
Pour votre culture informatique sachez qu'une fonction n'est pas obligée de renvoyer une valeur, on parlera alors dans ce cas plutôt de procédure.

# Les fonctions prédéfinies de python
Les fonctions prédéfinies
Il existe des fonctions internes à python (ou builtin).

abs(x)
Retourne une valeur absolue

>>> abs(-1)
1
all(iterable)
Retourne True si tous les éléments d'un élément itérable sont True

>>> liste = [True,True,True,1]
>>> all(liste)
True
any(iterable)
Retourne True si au moins un élément d'un élément itérable est True

>>> liste = [True,False, True]
>>> any(liste)
True
bin(x)
Convertit un integer en chaine de caractères binaires.

>>> bin(101)
'0b1100101'
callable(object)
Determine si un objet est callable.

>>> callable("A")
False
>>> callable(int)
True
str.capitalize()
La méthode capitalize permet de mettre une chaine de caractères au format Xxxxx

>>> "oLIviER".capitalize()
'Olivier'
choice([])
Retourne une valeur d'une liste aléatoirement.

>>> import random
>>> random.choice([1,2,3,4,5])
3
>>> random.choice([1,2,3,4,5])
2
str.count(string)
La méthode count compte le nombre d'occurences de la recherche demandée.

>>> "olivier".count("i")
2
dir(object)
Indique les noms de la structure de l'objet.

>>> dir(int)
['__abs__', '__add__', '__and__', '__class__', '__cmp__', '__coerce__', '__delattr__', '__div__', '__divmod__', '__doc__', '__float__', '__floordiv__', '__format__', '__getattribute__', '__getnewargs__', '__hash__', '__hex__', '__index__', '__init__', '__int__', '__invert__', '__long__', '__lshift__', '__mod__', '__mul__', '__neg__', '__new__', '__nonzero__', '__oct__', '__or__', '__pos__', '__pow__', '__radd__', '__rand__', '__rdiv__', '__rdivmod__', '__reduce__', '__reduce_ex__', '__repr__', '__rfloordiv__', '__rlshift__', '__rmod__', '__rmul__', '__ror__', '__rpow__', '__rrshift__', '__rshift__', '__rsub__', '__rtruediv__', '__rxor__', '__setattr__', '__sizeof__', '__str__', '__sub__', '__subclasshook__', '__truediv__', '__trunc__', '__xor__', 'bit_length', 'conjugate', 'denominator', 'imag', 'numerator', 'real']
str.endswith(str)
La méthode endswith test si une chaine de caractères se termine par la chaine demandée

>>> a = "olivier"
>>> a.endswith("r")
True
>>> a.endswith("er")
True
>>> a.endswith("é")
False
eval(expression,globals=None,locals=None)
Execute une chaine de caractères.

>>> v = 101
>>> eval('v+1')
102
str.find(string)
La méthode find trouve la première occurence de la recherche demandée.

>>> "olivier".find("i")
2
help(element)
Cette fonction vous retourne des informations sur l'utilisation de l'élément qui vous intéresse.

>>> help(int)

Help on class int in module __builtin__:

class int(object)
 |  int(x=0) -> int or long
 |  int(x, base=10) -> int or long
 |  
 |  Convert a number or string to an integer, or return 0 if no arguments
 |  are given.  If x is floating point, the conversion truncates towards zero.
 |  If x is outside the integer range, the function returns a long instead.
 |  
 |  If x is not a number or if base is given, then x must be a string or
 |  Unicode object representing an integer literal in the given base.  The
 |  literal can be preceded by '+' or '-' and be surrounded by whitespace.
 |  The base defaults to 10.  Valid bases are 0 and 2-36.  Base 0 means to
 |  interpret the base from the string as an integer literal.
 |  >>> int('0b100', base=0)
 |  4
hex
Convertit un nombre en valeur hexadécimale.

>>> hex(16)
'0x10'
str.isalnum()
Retoune True si tous les caractères sont alphanumériques et qu'il y a au moins un caractère. Sinon False.

>>> "25".isalnum()
True
>>> "25b".isalnum()
True
>>> "25bé".isalnum()
True
>>> "25bé@".isalnum()
False
>>> "-".isalnum()
False
>>> "_".isalnum()
False
>>> "".isalnum()
False
str.isalpha()
Retourne True si tous les caractères sont des lettres et qu'il y a au moins un caractère. Sinon False

>>> "x".isalpha()
True
>>> "-".isalpha()
False
>>> "12".isalpha()
False
>>> "jean-claude".isalpha()
False
>>> "jean claude".isalpha()
False
>>> "élise".isalpha()
True
str.isdigit()
Retourne True si tous les caractères sont numériques et qu'il y a au moins un caractère. Sinon False.

>>> "1".isdigit()
True
>>> "1.5".isdigit()
False
>>> "1,5".isdigit()
False
>>> "3b".isdigit()
False
>>> " ".isdigit()
False
str.islower()
Retoune True si tous les caractères sont en minuscule.

>>> "olivier".islower()
True
>>> "Olivier".islower()
False
str.isspace()
Retoune True si il n'y a que des espaces et au moins un caractère.

>>> " ".isspace()
True
>>> "jean louis".isspace()
False
>>> "    ".isspace()
True
str.istitle()
Retourne True si la chaine a un format titre.

>>> "Titre".istitle()
True
>>> "TitrE".istitle()
False
>>> "Titre de mon site".istitle()
False
>>> "Titre De Mon Site".istitle()
True
str.isupper()
Retourne True si tous les caractères sont en majucule et qu'il y a au moins un caractère.

>>> "OLIVIER".isupper()
True
>>> "Olivier".isupper()
False
>>> "OlivieR".isupper()
False
str.join(liste)
La méthode join transforme une liste en chaine de caractères.

>>> ":".join(["olivier", "engel"])
'olivier:engel'
len(s)
Retourne le nombre d'items d'un objet.

>>> len([1,2,3])
3
>>> len("olivier")
7
locals()
Retounr un dictionnaire avec les valeurs des variables en cours.

>>> locals()
{'a': 12, '__builtins__': , '__package__': None, 'i': 20, 'v': 101, 'liste': [True, False, True], '__name__': '__main__', '__doc__': None}
str.lower()
La méthode lower permet de mettre en minuscule une chaine de caractères.

>>> "OLIVIER".lower()
'olivier'
map(function, [])
Execute une fonction sur chaque item d'un élément itérable.

>>> def add_one(x):
...     return x + 1
... 
>>> map(add_one, [1,2,3])
[2, 3, 4]
max() / min()
Retourne la valeur la plus élévée pour max() et la plus basse pour min()

>>> max([1,3,2,6,99,1])
99
>>> max(1,4,6,12,1)
12
randint()
Retourne un int aléatoire.

>>> import random
>>> random.randint(1,11)
5
random()
Retourne une valeur aléatoire.

>>> import random
>>> random.random()
0.9563522652738929
str.replace(string, string)
La méthode replace remplace un segment d'une chaine de caractères par une autre:

>>> "olivier".replace("i", "a")
'olavaer'
reverse()
La méthode reverse inverse l'ordre d'une liste.

>>> x = [1,4,7]
>>> x.reverse()
>>> x
[7, 4, 1]
reversed([])
Retourne un itérateur inversé.

>>> list(reversed([1,2,3,4]))
[4, 3, 2, 1]
round(number)
Arrondi un nombre.

>>> round(1)
1.0
>>> round(1.2)
1.0
>>> round(1.5)
2.0
>>> round(1.7)
2.0
>>> round(-1.7)
-2.0
>>> round(-1.2)
-1.0
shuffle([])
Mélange aléatoirement une liste.

>>> import random
>>> x = [1,2,3,4,5]
>>> random.shuffle(x)
>>> x
[2, 5, 4, 1, 3]
str.startswith(prefix[, start[, end]])
Retourne True si la chaine commence par le préfix indiqué. Ce préfix peut être un tuple. Les paramètres start et end (optionnel) test la chaine à la position indiquée. Le test est sensible à la case.

>>> "olivier".startswith("ol")
True
>>> "olivier".startswith(("ol", "eng"))
True
>>> "olivier".startswith(("xxx", "eng"))
False
>>> "olivier".startswith("OL")
False
>>> "olivier".startswith("ol")
True
list.sort()
La méthode sort permet de trier une liste.

>>> l = [5,1,4,2,10]
>>> l.sort()
>>> l
[1, 2, 4, 5, 10]
sorted(iterable)
Tri un élément itérable.

>>> sorted([3,2,12,1])
[1, 2, 3, 12]
str.split(séparateur)
La méthode split transforme une chaine de caractères en liste.

>>> "olivier:engel".split(":")
['olivier', 'engel']
str.splitlines([keepends])
Retourne une liste des lignes de la chaine. Cette méthode utilise le saut à la ligne universel, le retour à la ligne n'est pas inclu, à moins de renseigner le paramètre keepends à True.

>>> "olivier\n\n\engel\n\ndéveloppeur".splitlines()
['olivier', '', '\\engel', '', 'développeur']
>>> "olivier\nengel\ndéveloppeur".splitlines()
['olivier', 'engel', 'développeur']
>>> "olivier\n\rengel\n\rdéveloppeur".splitlines()
['olivier', '', 'engel', '', 'développeur']
>>> "olivier\r\nengel\r\ndéveloppeur".splitlines()
['olivier', 'engel', 'développeur']
>>> "olivier\r\nengel\r\n\r\ndéveloppeur".splitlines()
['olivier', 'engel', '', 'développeur']
>>> "olivier\r\nengel\r\n\r\ndéveloppeur".splitlines(True)
['olivier\r\n', 'engel\r\n', '\r\n', 'développeur']
sum(iterable [,start])
Additionne les valeurs d'un élément itérable.

>>> sum([1,2,3])
6
str.title()
Transforme la chaine dans un format title.

>>> "Ceci est un titre".title()
'Ceci Est Un Titre'
upper()
La méthode upper permet de mettre en majuscule une chaine de caractères.

>>> "olivier".upper()
'OLIVIER'
zip(*iterables)
Permet de regrouper sous la forme d'un tuple les items de listes.

>>> a = ["olivier", "bruce", "john"]
>>> b = ["engel", "wayne", "Wayne"]
>>> zip(a,b)
[('olivier', 'engel'), ('bruce', 'wayne'), ('john', 'Wayne')]


# IF ELIF ELSE Python Conditions

Cette notion est l'une des plus importante en programmation. L'idée est de dire que si telle variable a telle valeur alors faire cela sinon cela.

Prenon un exemple, on va donner une valeur à une variable et si cette valeur est supérieur à 5, alors on va incrémenter la valeur de 1

>>> a = 10
>>> if a > 5:
...     a = a + 1
... 
>>> a
11
Que se passe-t-il si la valeur était inférieure à 5?

>>> a = 3
>>> if a > 5:
...     a = a + 1
... 
>>> a
3
On remarque que si la condition n'est pas remplie, les instructions dans la structure conditionnelle sont ignorées.

Condition if else
Il est possible de donner des instructions quelque soit les choix possibles avec le mot clé else.

>>> a = 20
>>> if a > 5:
...     a = a + 1
... else:
...     a = a - 1
... 
>>> a
21
Changeons uniquement la valeur de la variable a:
>>> a = 3
>>> if a > 5:
...     a = a + 1
... else:
...     a = a - 1
... 
>>> a
2
Condition elif
Il est possible d'ajouter autant de conditions précises que l'on souhaite en ajoutant le mot clé elif, contraction de "else" et "if", qu'on pourrait traduire par "sinon".

>>> a = 5
>>> if a > 5:
...     a = a + 1
... elif a == 5:
...     a = a + 1000
... else:
...     a = a - 1
... 
>>> a
1005
Dans cet exemple, on a repris le même que les précédent mais nous avons ajouté la conditions "Si la valeur est égale à 5" que se passe-t-il? Et bien on ajoute 1000.
Les comparaisons possibles
Il est possible de comparer des éléments:

==      égal à 
!=      différent de (fonctionne aussi avec )
>       strictement supérieur à 
>=      supérieur ou égal à
<       strictement inférieur à 
<=      inférieur ou égal à
Comment fonctionne les structures conditionnelles?
Les mots clé if, elif et else cherchent à savoir si ce qu'on leur soumet est True. En anglais True signifique "Vrai". Donc si c'est la valeur est True, les instructions concernant la condition seront exécutée.

Comment savoir si la valeur qu'on soumet à l'interpreteur est True? Il est possible de le voir directement dans l'interpréteur.

Demandons à python si 3 est égal à 4:

>>> 3 == 4
False
Il vous répondra gentiment que c'est False, c'est à dire que c'est faux.

Maintenant on va donner une valeur à une variable est on va lui demander si la valeur correspond bien à ce que l'on attend.

>>> a = 5
>>> a == 5
True
AND / OR
Il est possible d'affiner une condition avec les mots clé AND qui signifie "ET" et OR qui signifie "OU".

On veut par exemple savoir si une valeur est plus grande que 5 mais aussi plus petite que 10:

>>> v = 15
>>> v > 5 and v < 10
False
Essayons avec la valeur 7:

>>> v = 7
>>> v > 5 and v < 10
True
Pour que le résultat soit TRUE, il faut que les deux conditions soient remplies

Testons maintenant la condition OR

>>> v = 11
>>> v > 5 or v > 100
True
Le résultat est TRUE parce qu'au moins une des deux conditions est respectée.

>>> v = 1
>>> v > 5 or v > 100
False
Dans ce cas la aucune condition n'est respectée, le résultat est donc FALSE.

Chainer les comparateurs
Il est également possible de chainer les comparateurs:

>>> a, b, c = 1, 10, 100
>>> a < b < c
True
>>> a > b < c
False

# Les boucles for et while Python
Une boucle ( ou loop ) vous permet de répéter à l'infini des instructions selon vos besoins.

Le boucle while
En anglais "while" signifie "Tant que". Pour créer une boucle, il faut donc utiliser ce mot clé suivi d'une indication qui dit quand la boucle s'arrête.

Un exemple sera plus parlant:

On désire écrire 100 fois cette phrase:

"Je ne dois pas poser une question sans lever la main"

Ecrire à la main prend beaucoup de temps et beaucoup de temps x 100 s'est vraiment beaucoup de temps, et peu fiable, même pour les chanceux qui connaissent le copier-coller. Et un bon programmeur est toujours un peu fainéant perfectionniste, il cherchera la manière la plus élégante de ne pas répéter du code.

>>> i = 0
>>> while i < 10:
...     print("Je ne dois pas poser une question sans lever la main")
...     i = i +1
... 
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
Je ne dois pas poser une question sans lever la main
La boucle for
La boucle for permet de faire des itérations sur un élément, comme une chaine de caractères par exemple ou une liste.

Exemple:

>>> v = "Bonjour toi"
>>> for lettre in v:
...     print lettre
... 
B
o
n
j
o
u
r
 
t
o
i
Range
Il est possible de créer une boucle facilement avec range:

for i in range(0,100):
    print i
Stopper une boucle avec break
Pour stopper immédiatement une boucle on peut utiliser le mot clé break:

>>> liste = [1,5,10,15,20,25]
>>> for i in liste:
...     if i > 15:
...             print "On stoppe la boucle"
...             break
...     print i
... 
1
5
10
15
On stoppe la boucle

# Les modules et les packages en python

Jusqu'à présent nous avons réussi à créer des petits morceaux de code sans grand intérêt car très peu ambitieux. Le problème de l'interpréteur c'est qu'une fois celui-ci fermé votre travail est perdu.

L'idée d'un programme c'est d'enregistrer votre travail dans un fichier et ensuite de l'exécuter. Cela augmente votre productivité mais possède de nombreux avantages comme le copier-coller massif ou tout simplement le travail collaboratif. Lorsque du code est enregistré dans un fichier exécutable on parle de script.

Créer son premier script python
Tout d'abord vous devez créer un fichier avec l'extension .py -dans notre exemple on le nommera fiche.py - dans le dossier que vous voulez (l'emplacement n'a aucune importance).



Ouvrez ensuite le fichier.

Hello world
Le traditionnel hello world se fait ainsi:

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-
print "Bonjour monde"
La première ligne indique qu'il s'agit de code python. 
La deuxième ligne indique le type d'encodage utilisé. Je vous conseille toujours quelque soit votre projet et votre langage de programmation de passer par de l'UTF-8 et la troisème ligne vous connaissez déjà.

Exécuter un script python
Pour exécuter un script python sur ubuntu il vous suffit de lancer la commande suivante:

python /chemin_vers_votre_script/fiche.py
Faire interagir l'utilisateur
Un programme n'est pas très intéressant si l'utilisateur ne peut pas dialoguer avec celui-ci.

On va créer un petit script qui demande l'âge à l'utilisateur et on affichera cette valeur par la suite:

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

age = input("Quel est votre age? : ")
print "Vous avez %d ans" % age
A noter que si vous travaillez avec python 2.7, il est impossible de faire passer des données autres que numériques à la fonction input, pour python 2.7 on préférera utiliser la fonction raw_input qui fait sensiblement la même chose.

Les commentaires en python
Que vous soyez seul à développer vos scripts ou à plusieurs, il sera toujours indispensable de commenter votre travail. Par exemple si vous créez une fonction qui s'étale sur des centaines de lignes de code, il sera plus efficace d'écrire un petit descriptif de votre fonction au dessus de celle-ci plutôt que de devoir relire tout le code pour comprendre cette fonction des mois plus tard.

Les commentaires en python commencent par le signe #

Exemple:

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

# Cette fonction pose une question à l'utilisateur 
# et celui-ci devra répondre par un nombre obligatoirement

age = input("Quel est votre age? : ")
print "Vous avez %d ans" % age
Importer des fonctions d'autres fichiers
Pour les projets les plus ambitieux il sera vite important d'organiser son travail. Les fonctions vont se multiplier et il faudra les enregistrer dans des fichiers distincts pour plus de flexibilité.

Créons un autre fichier que nous nommerons func.py dans le même dossier que le fichier fiche.py

func.py

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

def ajoute_un(v):
    return v + 1
fiche.py

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

from func import *

age = input("Quel est votre age? : ")
print "Vous avez %d ans" % age

age_plus_un = ajoute_un(age)

print "Dans un an vous aurez %d ans" % age_plus_un
Instructions, fonctions, modules, packages
Nous avons donc vu que lorsque l'on regroupe des fonctions dans un fichier on crée un ensemble de fonctions que l'on nomme "module".

Lorsque l'on cherche à regrouper des modules, on parle de package.

Créer un package
Pour créer votre propre package, commencez par créer dans le même dossier que votre programme - un dossier portant le nom de votre package. Dans notre exemple, nous le nommerons "utils".

Dans ce dossier, créons le fichier suivant: __init__.py, cela indique à python qu'il s'agit d'un package. Ce fichier peut être vide, seule sa présence est importante.

Ensuite créons un fichier toujours dans ce réportoire utils que nous nommerons par exemple "operations.py"

Contenu du dossier de votre projet:



Contenu du dossier utils:



Maintenant éditons le fichier operations.py et créons une nouvelle fonction

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

def ajoute_deux(v):
    return v + 2
Puis ajoutons un appel vers cette fonction dans le fichier fiche.py

#!/usr/bin/python2.7
#-*- coding: utf-8 -*-

from func import *
from utils.operations import ajoute_deux

age = input("Quel est votre age? : ")
print "Vous avez %d ans" % age

age_plus_un = ajoute_un(age)

print "Dans un an vous aurez %d ans" % age_plus_un

age_plus_deux = ajoute_deux(age)

print "Dans un an vous aurez %d ans" % age_plus_deux
Alors que remarque-t-on? Tout d'abord on importe un package avec les mots clé from et import, ensuite pour appeler une fonction précise, on passe par la hiérarchie suivante:

from package.module import fonction
Si vous voulez importer toutes les fonctions d'un module, vous pouvez indiquer une étoile * qui signifie souvent en informatique "TOUS".

Les modules de python
Voici une liste de modules de base que vous serez amené un jour ou l'autre à utiliser.

random   : fonctions permettant de travailler avec des valeurs aléatoires
math     : toutes les fonctions utiles pour les opérations mathématiques (cosinus,sinus,exp,etc.)
sys      : fonctions systèmes
os       : fonctions permettant d'interagir avec le système d'exploitation
time     : fonctions permettant de travailler avec le temps
calendar : fonctions de calendrier
profile  : fonctions permettant d'analyser l'execution des fonctions
urllib2  : fonctions permettant de récupérer des informations sur internet
re       : fonctions permettant de travailler sur des expressions régulières
Les extensions des fichiers python
Il existe plusieurs extensions de fichier qui tournent autour de python:

.py  -> script modifiable
.pyc -> script compilé
.pyw -> script executé sans lancement de terminal (sous windows)