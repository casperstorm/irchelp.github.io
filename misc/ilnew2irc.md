---
title: The IRC Prelude
layout: default
datecreated: 4 July 2000
license: irchelp
redirect_from: /irchelp/ilnew2irc.html
---
<style>
	body {
		direction: rtl;
	}
</style>

# <span id="top">המבוא ל - IRC</span>

נכתב ע"י דיוויד קרבאלו(DC-isme) וג'וזף לו(Jolo)  
גירסה 1.2, עודכן לאחרונה ב04/07/2000  
תורגם לעברית מאנגלית ע"י דוד באום(MERKAVA)

המסמך המקורי נמצא
ב
<http://www.irchelp.org/faq/new2irc.html>

{% include new2irc_translations.md %}

## <span id="תוכן">תוכן</span>:

1.  [מה זה IRC, ואיך זה פועל?](#מהזה)

2.  [קצת פירוט](#פרטים)

3.  [דיבור והזנת פקודות](#תכלס)

4.  [לאן ללכת](#לאן)

5.  [סמיילים ושפה על קצה המזלג](#מילון)

6.  [קצת עצות](#עצות)

7.  [בעיות בשרתים, ובחירת השרת המתאים לך](#שרתים)

8.  [עזרה יותר מפורטת](#עזרהמ)

9.  [מילות אזהרה](#אזהרה)

## <span id="מהזה">1. מה זה IRC ואיך זה פועל?</span>

IRC או בתרגום צ'אט מבוסס אינטרנט מספקת דרך תקשורת בזמן אמת עם אנשים מכל
קצוות העולם. היא מורכבת ממספר
[רשתות](/networks/) שונות ומופרדות של
שרתי IRC, מכונות אשר מאפשרות למשתמשים(Users) להתחבר לIRC. רשתות הIRC
הגדולות הן: [EFnet](http://www.efnet.org)(רשת הIRC המקורית שלא פעם
מחוברים אליה יותר מ32,000 משתמשים בו-זמנית),
[Undernet](http://www.undernet.org),
[IRCnet](https://www.ircnet.com/), [Dalnet](http://www.dal.net)
ו[Libera.Chat](https://libera.chat/).

בדרך כלל משתמש(למשל את\\ה) מריץ(מפעיל) תוכנה(הקרויה 'לקוח' או 'client')
בשביל להתחבר לשרת(סרבר או server) באחת מ
[רשתות הIRC](/networks/). 
השרתים מעבירים (קולטים
ומשדרים) מידע ביינם לבין שרתים אחרים באותה רשת.  
לקוחות מומלצים:

  - יוניקס: [ircII](/clients/unix/ircii/)
  - ווינדווס: [mIRC](/clients/windows/mirc/) או
    [PIRCH](http://webarchive.loc.gov/all/20020914162855/http://www.pirchat.com/)
  - מקינטוש: [Ircle](/clients/mac/ircle_setup.html)

דאגו לקרוא את המסמכים הנוגעים ל'לקוח' שבחרת \!

לאחר שהתחברת לשרת באחת מרשתות הIRC, סביר להניח שתצטרף לערוץ(חדר שיחה או
channel) אחד או יותר ותושוחח עם אנשים אחרים באותו ערוץ.
ב[EFnet](http://www.efnet.org/) קיימים לעיתים קרובות יותר מ12,000
ערוצים, כאשר כל אחד מוקדש לנושא אחר. השיחה יכולה להיות או
ציבורית(שיחה שנערכת בערוץ וכל האנשים באותו ערוץ יכולים לצפות במה
שאתה מקליד) או שיחה פרטית(מסר או שיחה בין שני אנשים בלבד, שנמצאים או לא
נמצאים באותו או אותם ערוצים). רשת הIRC(י.ר.ס) היא לא משחק, ועל אף
האנונימיות שהיא מספקת יש לנהוג בכל המשתמשים בה בכבוד ובאנשים שאתה
משוחח איתם יש לנהוג כנו שהיית מתנהג אילו היית מדבר איתם בטלפון, אחרת
עלולות להיות השלכות חמורות \!

[\[ תוכן העניינים \]](#תוכן)

## <span id="פרטים">2. קצת פרטים</span>

שמות ערוצים מתחילים כמעט תמיד ב\#(סולמית), כמו למשל irchelp\#. אותם
ערוצים נחלקים בין כל משתמשי רשת י.ר.ס, לכן אינך חייב להיות מחובר
לאותו שרת כמו חבריך כדי להיות באותו ערוץ, אתה רק צריך להיות מחובר
לאותה רשת.  
ישנם גם ערוצים שמתחילים ב&(לסמל זה קוראים אמפרסנד) ולא ב\#(סולמית).
ערוצים אלו הם ערוצים 'מקומיים' ואינם נחלקים בין כל משתמשי הרשת אלא
רק בין משתמשי השרת.

כל משתמש בי.ר.ס ידוע בכינוי מסוים(nick), כמו Me16m או KuSiT17. בכדי
להמנע ממריבות ומחלוקות עם משתמשים אחרים, מומלץ לא לבחור כינוי נפוץ
מידי, למשל "דוד" תהיה בחירה לא חכמה במיוחד וגם לא מקורית. ברשתות
מסוימות הכינויים לא שייכים לאף-אחד, גם לא שמות ערוצים. דבר זה
יכול להוביל למחלוקות ותקלים, אם ממש בא לך להחזיק את הבעלות על כינוי
מסויים או ערוץ מסויים, יכול להיות שתעדיף רשתות עם שירותים(לשמירת
כינויים, ערוצים וגם מסרים) כמו [DALnet](http://www.dal.net),
[Undernet](http://www.undernet.org) או [רשתות
קטנות](/networks/) יותר.

ערוצים מופעלים ע"י מפעילי ערוצים(operators), או פשוט "אופים". אופ או
אופים של ערוץ שולטים בערוץ בכמה דרכים: ע"י הקביעה מי מורשה
להצטרף(ע"י נידוי או חרם\[באן או ban\]), האופ גם יכול לקבוע מי
יעוף(ע"י בעיטה\[kick\]), ואפילו ע"י הקביעה מי יכול ומי לא יכול
לדבר(ע"י קביעת הערוץ במצב מוצנע \[moderated\])\! מפעילי ערוצים
מחזיקים שליטה מלאה על הערוץ שלהם וסמכותם היא סופית וקובעת באותו
ערוץ. אם נאסרה עליך הכניסה לערוץ מסוים ואתה חושב שהדבר נעשה שלא בצדק
שלח מסר לאחד המפעילים של הערוץ, ובקש בצורה מנומסת שיסירו את נידוייך(ban)
מהערוץ. במידה ואתה מתקשה למצוא מפעיל של אותו ערוץ בדוק בחלק הבא של מאמר
זה על הפקודה who/. אם המפעיל או המפעילים בחרו להתעלם ממך או שפקודת who/
לא מגיבה(מאחר שהערוץ נמצא במצב סודי או s+), פשוט לך למקום אחר שבו אתה
רצוי.

שרתי י.ר.ס מנוהלים על-ידי מנהלי רשת(admins) ועל-ידי מפעילי י.ר.ס( IRC
operators או IRC ops). מפעילי י.ר.ס מנהלים את השרתים בעצמם, וברשת EFnet
כמו בהרבה רשתות אחרות, הם לא מתערבים בסיכסוכים אישיים, השתלטויות על
ערוצים, השבת תקן מפעיל ערוץ וכו'.. הם לא באמת מתפקדים כמפעילים.

[\[ תוכן העניינים \]](#תוכן)

## <span id="תכלס">3. דיבור והזנת פקודות</span>

פקודות וטקסט מוקלדים לאותו מקום. כברירת מחדל פקודות מקבלות את הקידומת
/(סלאש נמצא בד"כ משמל למקש השיפט הימני). אם ברשותך לקוח גרפי כמו
[mIRC](/clients/windows/mirc/) לווינדווס, הרבה מן הפקודות
יכולות להתבצע ע"י לחיצה על סמלים שונים בעזרת מצביע העכבר(סמן או
pointer). אע"פ כן מומלץ שתלמד תחילה את הפקודות הבסיסיות של י.ר.ס ואת
אופן השימוש בהן. כאשר אתה מזין פקודה הקדש תשומת לב מרובה לאיות(למשל
חיים\# join/ או חיים\# joint/) סביר להניח שהאופציה השניה תגרום לתגובה
בסגנון - "פקודה לא ידועה" מאחר שהפקודה join לא אויתה כראוי. כמו כן יש
להקפיד על קפיטליזציה(ההבדלה בין אות גדולה לקטנה באנגלית). הפקודות
הבסיסיות עובדות על כל הלקוחות הטובים.

למטה מובאות כמה דוגמאות פשוטות. יש להניח שהכינוי שלך הוא MeMe, ושאתה
בערוץ Israel\#.

חברך Yoav23 גם כן נמצא בisrael\# איתך וחברך gal-m-16 גם בי.ר.ס אבל לא
באותו ערוץ כמוך וכמו Yoav23. אתה יכול ליישם דוגמאות אלו באופן כללי
כאשר אתה מחליף את שם הערוץ בעערוץ המתאים ואת הכינוי בכינוי המתאים.

<div data-align="right">

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="text-align: right;"><p><strong>התגובה של י.ר.ס - מה קורה</strong></p></td>
<td><strong>אתה כותב</strong></td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>אתה מצטרף לערוץ israel#.</p></td>
<td>/join #israel</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>אתה מקבל פרטים על המשתמשים בערוץ israel#<br />
@ - מפעיל ערוץ, * - מפעיל י.ר.ס, +משתמש בעל 'קול'(v+)</p></td>
<td>/who #israel</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>כל המשתמשים בערוץ israel# רואים:<br />
היי כולם מה קורה? &lt;MeMe&gt;</p></td>
<td>היי כולם מה קורה?</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>כל המשתמשים בערוץ israel# רואים:<br />
הוא המלך הורדוס MeMe *</p></td>
<td>/me הוא הורדוס המלך</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>אתה עוזב את הערוץ israel# וכל המשתמש בו רואים מסר כמו:<br />
&lt;כי בא לי (MeMe(~sadi@ras2.jln.netvision.net.il &gt;</p></td>
<td>/leave #israel כי בא לי<br />
/part #israel כי בא לי</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>אתה מקבל מידע על Yoav23.</p></td>
<td>/whois Yoav23</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>אתה מקבל את המידע שכולם רואים עליך.</p></td>
<td>/whois MeMe</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>אתה משנה את הכינוי שלך לKuSON19. כל המשתמשים בערוץ רואים מסר:<br />
MeMe is now know as KuSON19</p></td>
<td>/nick KuSON19</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>Yoav23 ורק הוא מקבל מסר בפרטי:<br />
היי גבר</p></td>
<td>/msg Yoav23 היי גבר</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>אתה מקסל את המידע על העיכוב בינך ובין שאר משתמשי הערוץ israel#.</p></td>
<td>/ping #israel</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>מספק לך את המידע על העיכוב בינך ובין Yoav23 בלבד.</p></td>
<td>/ping Yoav23</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>פקודה זו תשלח לgal-m-16 בקשת לדי.סי.סי צ'אט. או במילים אחרות שיחה שלא עוברת דרך השרת של הי.ר.ס.<br />
בכדי שתוכל לשוחח עם gal-m-16 על גל להקיש<br />
dcc chat MeMe/ למרות שיש להניח שהוא פשוט יתבקש לענות בyes, no או ignore.<br />
די.סי.סי צ'אט הוא יותר מהיר ובטוח.</p></td>
<td>/dcc chat gal-m-16</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>לאחר שהוקמה תקשורת ד.ס.ס אתה שולח לgal-m-16 מסר. סימן השווה(=) לא נראה בצד השני. וgal-m-16 יקבל מסר:<br />
היי אתה בא למסיבה?</p></td>
<td>/msg =gal-m-16 היי, אתה בא למסיבה?</td>
</tr>
<tr class="odd">
<td style="text-align: right;"><p>ברוב הלקוחות(התוכנות) זה מקפחץ את קובץ העזרה.</p></td>
<td>/help</td>
</tr>
<tr class="even">
<td style="text-align: right;"><p>אתה מתנתק לחלוטין מרשת הי.ר.ס, וכל המשתמשים בערוצים שבהם שהית רואים:<br />
(לילה טוב!) MeMe: Signoff***</p></td>
<td>/quit לילה טוב!</td>
</tr>
</tbody>
</table>

</div>

**הערה**: כאשר אתה לא בערוץ, שורות שלא מוקדמות ע"י תו ה/ לא משפיעות,
ופקודות רבות פועלות באופן שונה אם בכלל.

[\[ תוכן העניינים \]](#תוכן)

## <span id="לאן">4. לאן ללכת</span>

אפשר ללמוד המון ע"י הצטרפות לערוצים והקשבה לזמן מה. למתחילים כדאי להצטרף
לערוצים: \#new2irc, \#newuser, \#newbies או chatback\#. אפשרויות יותר
צפופות הן chat\# וircbar\#. יש לציין שלכל רשת ישנם ערוצי מתחילים עם
שמות דומים אך חלק מהערוצים הנ"ל לא קיימים בכל רשת, לפחות לא בשמם הנ"ל.

בכדי לקבל מידע ועזרה על לקוחות mIRC, נסה להצטרף לערוץ mIRC\#, \#
new2mirc או mirchelp\#. אם ברצונך לשאול שאלות י.ר.ס כלליות הצטרף לערוצים
כמו \#irchelp או helpdesk\#.

בכדי להקים או ליצור ערוץ משלך(כאשר שם הערוץ הוא לדוגמא: הערוץשלי\# ואף
אחד אחר אינו מחזיק בבעלות עליו), הקלד הערוץשלי\# join/. הערוץ יווצר
מיידית ואתה תוגדר המפעיל שלו(op). ברשתות מסויימות כגון
[דאלנט](http://www.dal.net) ישנן אפשרויות ניהול ורישום ערוצים
מתקדמות אשר מאפשרות לך להחזיק בערוץ שלך ולנהלו לאורך זמן וביעילות.

[\[ תוכן העניינים \]](#תוכן)

## <span id="מילון">5. סמיילים ושפה על קצה המזלג</span>

:-) זהו פרצוף סמיילי, אם אתה לא רואים את החייוכון(סמיילי) הטו את רשכם
הצידה בכדי לראותו. חיכונים נועדו להביע רגשות ותחושות בד"כ כתגובה
למשהו שהמשתמש עשה. :-( הוא פרצוף עצוב. ;-) הוא קריצה. :\~\~( הוא
חייכון בוכה\[כמה אירוני\]. :-P אומר שהמשתמש מוציא את לשונו החוצה כאשר
השלב המתקדם הוא :-P\~\~ הזלת ריר. הסמיילים הנ"ל באים בכיוון ההפוך
ונקראים סמיילים שמאליים. למשל (-: זה סמיילי :-) וזה סמיילי שמאלי
באופן דומה ישנם מאות פרצופים שונים.

הנה רשימה קצרה מאוד של הקיצורים וראשי התיבות(האנגליים) הנפוצים ביותר
בי.ר.ס (ובד"כ בכל האינטרנט):

<div data-align="right">

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><ul>
<li>brb = be right back</li>
<li>bbl = be back later</li>
<li>nop\np = no problem</li>
<li>lol = laughing out loud</li>
<li>wtf = what the fuck</li>
<li>rotfl = rolling on the floor laughing</li>
</ul></td>
<td style="text-align: right;"><ul>
<li><p>חוזר עוד מעט</p></li>
<li><p>אני אחזור אח"כ</p></li>
<li><p>אין בעיה</p></li>
<li><p>מתפקע מצחוק</p></li>
<li><p>מה לעזאזל</p></li>
<li><p>מתפקע מצחוק על הריצפה</p></li>
</ul></td>
</tr>
<tr class="even">
<td><ul>
<li>bbfl = be back in a flash</li>
<li>ttfn = ta ta for now</li>
<li>imho = in my humble oppinion</li>
<li>imnsho = in my not so humble oppinion</li>
<li>j/k = just kidding</li>
<li>wb = welcome back</li>
<li>rtfm = read the fucking manual</li>
</ul></td>
<td style="text-align: right;"><ul>
<li>חוזר עוד שניה</li>
<li>להתראות לבינתיים</li>
<li>לפי דעתי הצנועה</li>
<li>לפי דעתי הלא כ"כ צנועה</li>
<li>בצחוק</li>
<li>ברוך שובך</li>
<li>תקרא את המניואל המזדיין</li>
</ul></td>
</tr>
</tbody>
</table>

</div>

  
[\[ תוכן העניינים \]](#תוכן)

## <span id="עצות">6. קצת עצות</span>

  - **אתיקה**  
    כאשר אתה כותב באנגלית אל תכתוב באותיות גדולות בלבד, LEMASHAL KAHA,
    זה נחשב לצעקה ולא לדיבור. כמו כן, אל תחזור על עצמך או
    'תציף'(flood) את הערוץ בעזרת הרבה שורות טקסט שהוזנו(או על-ידך או
    ע"י קובץ טקטס) בבת-אחת. בכדי למנוע אי-הבנות הימנע משמוש
    במינוח(terminology) לא תקין, כמו חדר שיחה במקום ערוץ ,או שם
    במקום כינוי.
     
    בזמן שהותך בערוץ ישר קו עם מפעיל הערוץ שבו אתה נמצא. אם תרגיז או
    תעורר זעם או כעס באחד ממפעילי הערוץ הוא מסוגל לבעוט אותך בכדי
    שתחדול, ואף לנדות(ban) אותך מלחזור לערוץ. רצוי לא לפרסם בערוצים,
    לא בפרטי, ולא בערוץ עצמו, פרסום בערוץ בד"כ גורם לנידויים ארוכי תווך
    כמו שעה ואף שעתיים. מצד שני, בערוצים מסוימים ישנם מפעילים תאווי כח
    ושליטה שעשויים לבעוט ואף לנדות משתמש ללא סיבה נראית לעין. אם זה
    המצב בערוץ שבו אתה נמצא, או שמטרידים אותך באותו ערוץ, פשוט עזוב\!
    ישנם אלפי ערוצים אחרים ואין סיבה להתחנן למפעיל נרגן.
  - **נותקת מרשת הי.ר.ס אחרי שהקלדת** **list/** **(בשביל לקבל את רשימת
    הערוצים)**  
    אם מותקת מהשרת לאחר שהקלדת list/, נסה להחליף שרת. אם זה לא עזר, הכנס
    לדף הבית של הרשת בה אתה נמצא ושם תמצא קישור לעמוד שבו רשומים כל
    החדרים.  
    ב[EFnet](/chanlist/) זה נמצא
    ב[chanlist](/chanlist/).
  - **הטרדות והתקפות**  
    אם מישהו מתחיל להטריד אותך או להציף אותך, עזוב את הערוץ. במידה ולא
    מתחשק לך לעזוב רק בגלל מטריד אחד פשוט הקלד ignore nick/ (כאשר nick
    הוא האדם שאתה מבקש להתעלם ממנו). ליתר פירוט אם אתה משתמש
    [mIRC](/clients/windows/mirc/) , בקר בעמוד [ההגנה
    מהצפות](/clients/windows/mirc/flood.html) שלנו.
    אם אתה משתמש ב[ircii](/clients/unix/ircii/) הקלד
    [help ignore/](/clients/unix/ircii/commands/irciihelp/ignore.html).
    מומלץ לקבוע את מצב(mode) המשתמש שלך ל i+ (בלתי נראה או
    invisible) בכדי להמנע ממסרים לא רצויים והטרדות - אם אתה במצב
    'בלתי-נראה' רק המשתמשים בערוץ שלך יכולים לראות את הכינוי שלך
    ולדעת שאתה מחובר.
     
    אם מישהו מרסק או מנתק אותך, העף מבט בדף 
	[מניעת השירותים או התקפות ניוקים(Nuke)](/nuke/). אתה גם יכול
    לשמור יומן(log) ולדווח על שימוש לרעה אם זה עובר על הכללים שנראים
    ע"י הקלדה motd/ (מסר היום או message of the day). ניתן לראות את
    תוכן 'מסר היום' בחלון המצב(status) מייד לאחר ההתחברות.

[\[ תוכן העניינים \]](#תוכן)

## <span id="שרתים">7. בעיות בשרתים, ובחירת השרת המתאים לך</span>

נכון לעכשיו אתה מסוגל לשוחח ולצ'וטט בי.ר.ס כמעט ללא בעיות. אבל... לבעיות
יש את התכונה להתעורר ולגרום לבעיות ברגע הכי לא מתאים.

  - **נט-ספליט(net splits)**  
    רשתות יכולות להתפרק לגורמיהין למצב זה קוראים נט-ספליט. מה שקורה הוא
    כזה, מאחר שכל רשת בנויה מעשרות שרתים שונים, יכולה להיווצר בעיית
    תקשורת בין שרתים שונים באותה רשת כאשר השרתים עמוסים. כאשר השרת
    עמוס הוא משקיע הרבה רוחב פס(שטח של העברת נתונים) למשתמשים על אותו
    שרת ואין לו מספיק רוחב פס להתקשר עם שרתים אחרים. נט-ספליטים קורים
    הרבה אך בד"כ הם מאוד קצרים ולא עורכים יותר מדקה וחצי. כאשר קורה
    נט-ספליט משתמש או מתנתק מהרשת(אוטומטית) או שנשאר מחובר אבל רק לשרת
    שלו או לשרת שלו ועוד קצת שרתים.
  - **עיכוב(לאג או lag)**  
    בעיה יותר נפוצה היא העיכוב(lagging). בעיכוב בוא הוא זמן שעובר בין
    הרגע שלחצת אנטר לבין הרגע שהטקסט הופיע אצל משתמש אחר או ערוץ
    מסויים. [בחירת שרת](/networks/servermap.html)
    שקרוב לביתך עוזרת להפחית את העיכוב במידה מסוימת. את העיכוב ניתן
    למדוד ע"י שימוש בפקודה ping/. אחרי שבררת מה השרת היותר מהיר עבור
    עליו או ע"י בחירתו מתוך תפריט file\\optins\\connect או ע"י הקשת
    הפקודה server server.name.here/.
  - [**רשימת שרתים**](/networks/)  
    ברוב הלקוחות, ע"י הקלדה links/ ניתן לראות רשימה של שרתים ברשת בה אתה
    משתמש. השתמש בפקודה זו בחסכנות, לא יותר מפעמיים רצוף, או שהרשת תטעה
    ותחשוב אותך לעושה צרות.
  - **משחק הפינג פונג**  
    \!Ping? Pong בחלון המצב רק אומר שהשרת בדק אותך לבדוק שאתה מחובר. מה
    שקורה הוא כזה, השרת שולח ברשת ?Ping לך ואם אתה מחובר
    [mIRC](/clients/windows/mirc/) עונה אוטומטית ב\!Pong
    אין לך מה לדאוג בקשר לכך.
  - **תזכורת בקשר לשיחת לקוח ללקוח ישירה(DCC - Direct Client
    Communication)**  
    פקודת הdcc chat/ יכולה לשמש לשיחה יותר בטוחה ןהעיקר חופשיה מעיכוב
    ונט-ספליטים. ברוב הלקוחות ניתן להקים תקשורת לקוח ישירה(DCC) ע"י
    הקשה dcc chat Nick\_to\_chat\_with/. בכדי לדבר דרך ההתקשרות הזו יש
    להקיש  
    מה שבא לך לכותב msg =nick/. בmIRC אתה גם יכול להתחיל התקשרות לקוח
    ישירה(DCC) ע"י בחירת DCC ולאחר מכן Chat מתוך התפריט ואז הקשת
    הכינוי שאיתו אתה מעונין לשוחח. חלון חדש נפתח לשם תקשורת לקוח
    ישירה.

[\[ תוכן העניינים \]](#תוכן)

## <span id="עזרהמ">8. עזרה יותר מפורטת</span>

לעזרה יותר מפורטת בקשר לנושאים אלו כמו גם בקשר לפקודות אחרות, בקר באתר
שלנו <http://www.irchelp.org/>. שם תוכל למצוא הרבה [קבצי
עזרה](/faq/) כגון:

  - [י.ר.ס למתקדמים](/faq/ircprimer.html)
  - [שאלות שכיחות](/faq/altircfaq.html)
    ב[alt.irc](news:alt.irc)
  - [IRC tutotial](/faq/irctutorial.html)

באתרים הבאים אתה תוכל למצא עזרה יותר מתקדמת על לקוחות י.ר.ס כולל:

  - [לקוחות](/clients/unix/ircii/)
    [irii](/clients/unix/ircii/) ו
	[תסריטי ircii](/script/)
  - [לקוחות מקינטוש](/clients/mac/)
  - [לקוחות mIRC](/clients/windows/mirc/) לחלונות

מחפש לקוחות אחרים? אם כן, המקור המקיף ביותר ללקוחת י.ר.ס נמצאב
ב[Undernet FTP Archive](ftp://ftp.undernet.org/pub/irc/clients/) או
ב[Undernet WWW archive](http://clients.undernet.org/). הלקוחות מאורגנים
בקבוצות כמו למשל: חלונות, מקינטוז, DOS, אמיגה, ג'אווה וכו'.

ללקוח הmIRC ישנם קבצי עזרה מעולים שנכתבו ע"י [Tjerk Vonck](mailto:mirc@dds.nl).
בחר בircinttro.hlp מתפריט עזרה.

[\[ תוכן העניינים \]](#תוכן)

## <span id="אזהרה">9. מילות אזהרה</span>

**תסריטי י.ר.ס(IRC scripts)** הם שורה של פקודות שהלקוח שלך יריץ(יבצע).
הרבה תסריטים שאולי אף היו טובים ובטוחים במקור, שונו כך שהם מסוכנים
ויכולים לגרום לך נזק רב ו\\או לחשוף את תוכן השיחות שלך. כמו בחיים
האמיתיים גם בתסריטי י.ר.ס אל תקבל דבר מאיש לא מוכר או שלא ניתן לבטוח
בו. קרו ויקרו הרבה מקרים של חשפיפת מידע ו\\או מחיקתו, אז למה שזה יהיה
אתה?\! **לעולם אבל לעולם** **אל** תקבל תסריט שאינך יודע מה כל שורה בו
עושה, אפילו מחבר, כי בהרבה מקרים גם לחברך אין את המומחיות והידע לגלות
את כל הדלתות האחוריות(backdoors) בתסריט או סתם שורות הרסניות.

**קבלת התקשרות לקוח ישירה אוטומטית(Automatic DCC get)** היא רעיון גרוע
מאין כמותו\! כל עוד האופציה הזו פועלת אתה ומחשבך פגיעים לשורה של
אירועים נחל מהתנתקות מהרשת וכלה דרך קבלת וירוס שתתבצע ללא הסכמתך
ועד להפעלת תסריטים זדוניים על מחשבים אחרים דרך המחשב שלך.

[\[ תוכן העניינים \]](#תוכן)

תודות מיוחדות ל:

FreeSoft, pyrsm, hershey, turtle, Ariell \#irchelp on EFnet ומפעילים
אחרים בערוץ

עכשיו לאחר שקראת את המדריך למתחיל, היכנס לי.ר.ס ותהנה\! אם אתה מעונין
ללמוד יותר בדוק את המסמכים הרבים ב  
[IRChelp home page\#](/).

**הערה:** המסמך כולו מנוסח בלשון זכר יחיד
רק לשם הקלות שבענין ולשם הסדר הטוב אך כל מה שנכתב במסמך זה מיועד גם
לבנות המין היפה (-: .  
אם יש לכם הערות, שאלות, מענות, תיקונים, טעויות או מכתבי נאצה כיתבו(אפשר
בעברית) לי ב<baumd@hotmail.com>