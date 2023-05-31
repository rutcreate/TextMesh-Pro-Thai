# textmeshpro-thai-3.0.6
v2.1.1<br>
https://github.com/rutcreate/TextMesh-Pro-Thai

Unity 5 or Lower<br>
https://gist.github.com/allfake/d4fde9c573eaa4d5461a07ad446faf18

## How to
### Step 1
Goto <b>/Packages/manifest.json</b> in your project and change<br>
"com.unity.textmeshpro": "3.0.6"<br>
to<br>
"com.unity.textmeshpro": "https://github.com/phumpnw/textmeshpro-thai-3.0.6.git"
### Step 2
Copy character to new unicode and adjust position by font editor (https://fontforge.org/en-US/downloads/)
```
 // Lower level characters 
private const int SARA_U = 3640;
private const int SARA_UU = 3641;
private const int PHINTHU = 3642;

// Lower level characters after pullDown
private const int SARA_U_DOWN = 63256;
private const int SARA_UU_DOWN = 63257;
private const int PHINTHU_DOWN = 63258;

// Upper level 1 characters
private const int MAI_HAN_AKAT = 3633;
private const int SARA_AM = 3635;
private const int SARA_I = 3636;
private const int SARA_Ii = 3637;
private const int SARA_Ue = 3638;
private const int SARA_Uee = 3639;
private const int MAI_TAI_KHU = 3655;

// Upper level 1 characters after shift left
private const int MAI_HAN_AKAT_LEFT_SHIFT = 65548;
private const int SARA_I_LEFT_SHIFT = 65566;
private const int SARA_Ii_LEFT_SHIFT = 65567;
private const int SARA_Ue_LEFT_SHIFT = 65568;
private const int SARA_Uee_LEFT_SHIFT = 65569;
private const int MAI_TAI_KHU_LEFT_SHIFT = 65564;

// Upper level 2 characters
private const int MAI_EK = 65549;
private const int MAI_THO = 65552;
private const int MAI_TRI = 65555;
private const int MAI_CHATTAWA = 65558;
private const int THANTHAKHAT = 65561;
private const int NIKHAHIT = 3661;

// Upper level 2 characters after pull down
private const int MAI_EK_DOWN = 3656;
private const int MAI_THO_DOWN = 3657;
private const int MAI_TRI_DOWN = 3658;
private const int MAI_CHATTAWA_DOWN = 3659;
private const int THANTHAKHAT_DOWN = 3660;

// Upper level 2 characters after pull down and shift left
private const int MAI_EK_PULL_DOWN_AND_LEFT_SHIFT = 65550;
private const int MAI_THO_PULL_DOWN_AND_LEFT_SHIFT = 65553;
private const int MAI_TRI_PULL_DOWN_AND_LEFT_SHIFT = 65556;
private const int MAI_CHATTAWA_PULL_DOWN_AND_LEFT_SHIFT = 65559;
private const int THANTHAKHAT_PULL_DOWN_AND_LEFT_SHIFT = 65562;

// Upper level 2 characters after shift left
private const int MAI_EK_LEFT_SHIFT = 65551;
private const int MAI_THO_LEFT_SHIFT = 65554;
private const int MAI_TRI_LEFT_SHIFT = 65557;
private const int MAI_CHATTAWA_LEFT_SHIFT = 65560;
private const int THANTHAKHAT_LEFT_SHIFT = 65563;
private const int NIKHAHIT_LEFT_SHIFT = 65565;

// Up tail characters
private const int PO_PLA = 3611;
private const int FO_FA = 3613;
private const int FO_FAN = 3615;
private const int LOchULA = 3628;

// Down tail characters
private const int THO_THAN = 3600;
private const int YO_YING = 3597;
private const int DOchADA = 3598;
private const int TO_PATAK = 3599;
private const int RU = 3620;
private const int LU = 3622;

// Cut tail characters
private const int THO_THAN_CUT_TAIL = 65544;
private const int YO_YING_CUT_TAIL = 65541;

// for exploded SARA_AM (NIKHAHIT + SARA_AA)
private const int SARA_AA = 3634;
```

### Step 3
Generate font in unity and custom <b>Character set</b> to range or hex https://gist.github.com/allfake/1d5a64c2a1eca36a660c


## Test Text
```
กก่ก้ก๋ก๊ก็ก์กํกิกีกืกึกำกุกูกฺก
กึ่กึ้กึ๋กึ๊กึ์
ปป่ป้ป๋ป๊ป็ป์ปํปิปีปืปึปำปุปูปฺป
ปึ่ปึ้ปึ๊ปึ๋ปึ์
ฬฬ่ฬ้ฬ๋ฬ๊ฬ็ฬ์ฬํฬิฬีฬืฬึฬำฬุฬูฬฺฟ
ฬึ่ฬึ้ฬึ๊ฬึ๋ฬึ์
ฐฐ่ฐ้ฐ๋ฐ๊ฐ็ฐ์ฐํฐิฐีฐืฐึฐำฐุฐูฐฺฐ
ฏฏ่ฏ้ฏ๋ฏ๊ฏ็ฏ์ฏํฏิฏีฏืฏึฏำฏุฏูฏฺฏ
ฎฎ่ฎ้ฎ๋ฎ๊ฎ็ฎ์ฎํฎิฎีฎืฎึฎำฎุฎูฎฺฎ
ญญ่ญ้ญ๋ญ๊ญ็ญ์ญํญิญีญืญึญำญุญูญฺญ
`1234567890-=qwertyuiop[]\asdfghjkl;'zxcvbnm,./
`1234567890-=QWERTYUIOP[]\ASDFGHJKL;'ZXCVBNM,./
-ๅ/_ภถุึคตจขชๆไำพะัีรนยบลฃฟหกดเ้่าสวงผปแอิืทมใฝ
%+๑๒๓๔ู฿๕๖๗๘๙๐"ฎฑธํ๊ณฯญฐ,ฅฤฆฏโฌ็๋ษศซ.()ฉฮฺ์?ฒฬฦ
```


## Credit
credit : https://github.com/rutcreate | https://github.com/allfake
