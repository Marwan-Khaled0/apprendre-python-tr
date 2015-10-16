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


