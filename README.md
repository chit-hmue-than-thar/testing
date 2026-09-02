# Burma Calendar (မြန်မာပြက္ခဒိန်)

![Burma Calendar Preview](./social-preview.png)

ပုံတွေနဲ့ အချက်အလက်တွေကို **ပြည်ထောင်စုသမ္မတမြန်မာနိုင်ငံတော် အစိုးရပြန်တမ်း** နဲ့ **မြန်မာ့ပြက္ခဒိန် အစဉ်အလာတွေ** ကို အခြေခံပြီး ကိုးကားထားပါတယ်။

ဒီဇိုင်းနဲ့ Icon တွေအတွက် [Lucide Icons](https://lucide.dev/) နဲ့ [Tailwind CSS](https://tailwindcss.com/) ကို သုံးထားပါတယ်။

> **Summary**
>
> ခုနှစ်နဲ့ လကို ရွေးမယ် -> ရလာတဲ့ ရက်စွဲအပေါ်မူတည်ပြီး မြန်မာသက္ကရာဇ်နဲ့ မြန်မာလတွဲကို တွက်ချက်မယ် -> ရုံးပိတ်ရက် Data တွေနဲ့ ချိတ်ပြီး Calendar Grid ပေါ်မှာ Highlight လုပ်မယ် -> ၃ လစာ အားလပ်ရက်တွေကို Sidebar မှာ စုစည်းကြည့်မယ် -> ရွေးထားတဲ့လအလိုက် မြန်မာ့ရာသီ ၃ မျိုး (ဆောင်း၊ နွေ၊ မိုး) အလိုက် Seasonal Theme ကို အလိုအလျောက် ပြောင်းပေးမယ်။

---

### 🌟 အဓိကလုပ်ဆောင်ချက်များ (Procedure Steps)

1. **ခုနှစ်နှင့် လ ရွေးချယ်နိုင်ခြင်း (Month & Year Selection)**

   * ၂၀၂၄ မှ ၂၀၂၇ အထိ ကြိုက်တဲ့ ခုနှစ်နဲ့ လကို ပြောင်းကြည့်နိုင်ပါတယ်။ Dropdown ကနေ ရွေးနိုင်သလို Next / Previous ခလုတ်တွေနဲ့လည်း လွယ်လွယ်ကူကူ ရွှေ့နိုင်ပါတယ်။

   * လက်ရှိလနဲ့ ရက်စွဲဆီ ပြန်သွားချင်ရင် **"ဒီနေ့ (Today)"** ခလုတ်ကို နှိပ်လိုက်ရုံပါပဲ။

2. **ပြက္ခဒိန်ဇယားကွက် ဖော်ပြခြင်း (Calendar Grid View)**

   * တနင်္ဂနွေကနေ စနေနေ့အထိ ၇ ရက် Grid နဲ့ Calendar ကို ပြထားပြီး အင်္ဂလိပ်ရက်စွဲ (Gregorian Date) နဲ့ မြန်မာဂဏန်းရက်စွဲ (၁၊ ၂၊ ၃ ...) ကို တစ်ရက်ချင်းစီ တွဲကြည့်နိုင်ပါတယ်။

   * စနေ၊ တနင်္ဂနွေ (Weekend) ရက်တွေ၊ ဒီနေ့ရက် (Today) နဲ့ အစိုးရရုံးပိတ်ရက် (Public Holidays) တွေကို အရောင်နဲ့ Badge တွေခွဲပြီး တစ်ချက်ကြည့်တာနဲ့ သိနိုင်အောင် ပြထားပါတယ်။

3. **မြန်မာသက္ကရာဇ်နှင့် လတွဲများ တွက်ချက်ပြသခြင်း (Myanmar Era & Month Pairs)**

   * Header မှာ ရွေးထားတဲ့ လအလိုက် သက်ဆိုင်တဲ့ **မြန်မာသက္ကရာဇ် (ဥပမာ - ၁၃၈၆ ခု)** နဲ့ **မြန်မာလတွဲ (ဥပမာ - တပေါင်း / တန်ခူး)** ကို အလိုအလျောက် တွက်ပြီး ပြပေးပါတယ်။

   * သင်္ကြန်ကာလ (ဧပြီလ) မှာ နှစ်ဟောင်းကနေ နှစ်သစ်ကို ကူးတဲ့အချိန်ရှိတာကြောင့် သက္ကရာဇ် ၂ ခုကို ခွဲခြားပြီး စနစ်တကျ တွက်ထားပါတယ်။

4. **၃ လတာ အားလပ်ရက်စာရင်း (3-Month Holiday Overview Sidebar)**

   * လက်ရှိလအပါအဝင် နောက်လာမယ့် ၂ လ၊ စုစုပေါင်း ၃ လစာ အစိုးရရုံးပိတ်ရက်တွေကို Sidebar မှာ တစ်ခါတည်း ကြည့်နိုင်ပါတယ်။ လတစ်လချင်းစီမှာ ဘယ်နှရက်ပိတ်လဲဆိုတာနဲ့ အားလပ်ရက်အမည်တွေကိုပါ တွဲပြီး ပြထားပါတယ်။

5. **မြန်မာ့ရာသီ ၃ မျိုးအလိုက် Adaptive UI Theme စနစ် (Seasonal Theming Engine)**

   * မြန်မာနိုင်ငံရဲ့ ရာသီ ၃ မျိုးအလိုက် UI Theme ကလည်း အလိုအလျောက် ပြောင်းသွားပါမယ်:

     * ❄️ **ဆောင်းရာသီ (Cool Season - နိုဝင်ဘာ မှ ဖေဖော်ဝါရီ)** : အေးမြကြည်လင်တဲ့ Blue Frost Palette

     * ☀️ **နွေရာသီ (Hot Season - မတ် မှ မေ)** : နွေးထွေးတောက်ပတဲ့ Sunlight Amber Palette

     * 🌧️ **မိုးရာသီ (Rainy Season - ဇွန် မှ အောက်တိုဘာ)** : စိမ်းလန်းစိုပြေတဲ့ Emerald Green Palette

   * Dark Mode သုံးတာပဲဖြစ်ဖြစ် Light Mode သုံးတာပဲဖြစ်ဖြစ် Season Theme နဲ့ လိုက်ဖက်အောင် အသုံးပြုနိုင်ပါတယ်။

6. **PWA (Progressive Web App) & Offline အသုံးပြုနိုင်ခြင်း**

   * ဖုန်းနဲ့ Desktop နှစ်မျိုးလုံးမှာ Native App တစ်ခုလို Install လုပ်ပြီး သုံးနိုင်ပါတယ်။ Internet မရှိတဲ့အချိန်မှာလည်း Calendar ကို ဆက်ပြီး ဖွင့်ကြည့်နိုင်အောင် Offline Support ထည့်ထားပါတယ်။

---

### 📊 ဒေတာဖွဲ့စည်းပုံ အချိတ်အဆက် (Holiday Data Mind Map)

![Holiday Data Mind Map](./holiday-mindmap.svg)

> **Mind Map ဒေတာဖွဲ့စည်းပုံ ရှင်းလင်းချက်:**
>
> * **Year Root (ခုနှစ်အဆင့်):** `2026`, `2027` စတဲ့ ခုနှစ်တစ်ခုချင်းစီကို Root Key အဖြစ် ခွဲထားပါတယ်။
>
> * **Holidays Collection (ပိတ်ရက်များ အစုအဝေး):** သက်ဆိုင်ရာ ခုနှစ်အောက်မှာ အဲ့ဒီနှစ်ရဲ့ အားလပ်ရက် Data တွေကို Array ပုံစံနဲ့ သိမ်းထားပါတယ်။
>
> * **Month & Details Node (လနှင့် အသေးစိတ် အချက်အလက်များ):**
>
>   * `month`: ပိတ်ရက်ကျရောက်တဲ့ လအမည် (ဥပမာ - `January`, `February`)
>
>   * `name`: ရုံးပိတ်ရက်အမည် (ဥပမာ - `နိုင်ငံတကာနှစ်သစ်ကူး`၊ `ပြည်ထောင်စုနေ့ & တရုတ်နှစ်သစ်ကူး`၊ `လွတ်လပ်ရေးနေ့`)
>
>   * `total_days`: အဲ့ဒီအားလပ်ရက်အတွက် စုစုပေါင်း ပိတ်ရက်အရေအတွက် (ဥပမာ - `4 days`, `6 days`, `1 day`)

---

### 👥 Participants

1. [Sann Lynn Htun](https://github.com/sannlynnhtun-coding)

2. [Yoke Sann](https://github.com/yokesann)

---

### 🤝 Contributors

<table>

  <thead>

   <tr>

```
<th colspan="2">Contributors</th>
```

   </tr>

  </thead>

  <tbody>

   <tr>

```
<td align="center">

 <a href="https://github.com/sannlynnhtun-coding">

   <img src="https://github.com/sannlynnhtun-coding.png" width="75px;" alt="sannlynnhtun-coding"/><br />

   <sub><b>sannlynnhtun-coding</b></sub>

 </a>

</td>

<td align="center">

 <a href="https://github.com/yokesann">

   <img src="https://github.com/yokesann.png" width="75px;" alt="yokesann"/><br />

   <sub><b>yokesann</b></sub>

 </a>

</td>
```

   </tr>

  </tbody>

</table>

---

### 💡 Changes & Credit Owner

* **၂၀၂၇ ခုနှစ် အစိုးရရုံးပိတ်ရက် ဒေတာများ ဖြည့်စွက်ခြင်း**

  [holidays-2027.json](file:///d:/testing/src/data/holidays-2027.json) ထဲမှာ ၂၀၂၇ ခုနှစ်အတွက် Bridge Holidays နဲ့ Public Holidays Data တွေကို ကူညီဖြည့်ထားပါတယ်။

* **မြန်မာသက္ကရာဇ်နှင့် ရာသီအလိုက် Theme ပြောင်းလဲခြင်း Logic**

  သင်္ကြန်ကူးတဲ့အချိန်မှာ သက္ကရာဇ်ဘယ်လိုပြောင်းမလဲဆိုတဲ့ Calculation Logic နဲ့ မြန်မာ့ရာသီ ၃ မျိုး (ဆောင်း၊ နွေ၊ မိုး) အလိုက် အရောင်အသွေးပြောင်းတဲ့ Theme System ကို ရေးသားဖြည့်စွက်ထားပါတယ်။

---

### 💻 Reference Code & Usage Examples

အောက်မှာ အဓိက Logic တွေကို Example Code နဲ့အတူ ထည့်ပေးထားပါတယ်။ ဒီ Code တွေကို Project ထဲမှာ စမ်းကြည့်နိုင်သလို အခြား Project တွေမှာလည်း လိုအပ်သလို ပြန်သုံးနိုင်ပါတယ်။

#### ၁။ အင်္ဂလိပ်ဂဏန်းမှ မြန်မာဂဏန်းသို့ ပြောင်းလဲခြင်း (Myanmar Numerals Converter)

အင်္ဂလိပ်ဂဏန်း `0` ကနေ `9` အထိကို မြန်မာဂဏန်း `၀` ကနေ `၉` အထိ ပြောင်းပေးတဲ့ Logic ဖြစ်ပါတယ်။ ခုနှစ် (ဥပမာ - 2026 ကို "၂၀၂၆") ဒါမှမဟုတ် ရက်စွဲ (ဥပမာ - 12 ကို "၁၂") တွေမှာ အသုံးပြုနိုင်ပါတယ်။

```typescript
const MYANMAR_DIGITS: Record<string, string> = {

  '0': '၀', '1': '၁', '2': '၂', '3': '၃', '4': '၄',

  '5': '၅', '6': '၆', '7': '၇', '8': '၈', '9': '၉',

};

export function toMyanmarNumerals(value: number | string): string {

  return String(value)

    .split('')

    .map((digit) => MYANMAR_DIGITS[digit] ?? digit)

    .join('');

}
```

စမ်းကြည့်ရင်:

* `toMyanmarNumerals(2026)` → `၂၀၂၆`
* `toMyanmarNumerals(12)` → `၁၂`

---

#### ၂။ မြန်မာသက္ကရာဇ် တွက်ချက်ခြင်း (Myanmar Era Calculation)

မြန်မာသက္ကရာဇ်က သင်္ကြန်ကာလမှာ နှစ်သစ်ကူးတာကြောင့် ဇန်နဝါရီကနေ မတ်လအထိဆိုရင် `(ခုနှစ် - ၆၃၉)` နဲ့ တွက်ပြီး မေလကနေ ဒီဇင်ဘာလအထိဆိုရင် `(ခုနှစ် - ၆၃၈)` နဲ့ တွက်ပါတယ်။

ဧပြီလမှာတော့ သင်္ကြန်ကာလဖြစ်တာကြောင့် နှစ်ဟောင်းနဲ့ နှစ်သစ် သက္ကရာဇ် ၂ ခုကို `(ဥပမာ - "၁၃၈၇ / ၁၃၈၈")` လိုမျိုး တွဲပြီး ပြပါတယ်။

```typescript
export function getMyanmarEraLabel(date: Date): string {

  const year = date.getFullYear();

  const month = date.getMonth();

  if (month === 3) {

    return `${toMyanmarNumerals(year - 639)} / ${toMyanmarNumerals(year - 638)}`;

  }

  return toMyanmarNumerals(year - (month < 3 ? 639 : 638));

}
```

စမ်းကြည့်ရင်:

* ဇန်နဝါရီလ ၁ ရက် ၂၀၂၆ → `getMyanmarEraLabel(new Date(2026, 0, 1))` → `၁၃၈၇`
* ဧပြီလ ၁၅ ရက် ၂၀၂၆ → `getMyanmarEraLabel(new Date(2026, 3, 15))` → `၁၃၈၇ / ၁၃၈၈`

---

#### ၃။ မြန်မာ့ရာသီ ၃ မျိုး ခွဲခြားတွက်ချက်ခြင်း (Myanmar Season Logic)

မြန်မာနိုင်ငံရဲ့ ရာသီဥတု ၃ မျိုးအလိုက် လတွေကို အောက်ပါအတိုင်း ခွဲထားပါတယ်:

* ဆောင်းရာသီ (Cool): နိုဝင်ဘာ၊ ဒီဇင်ဘာ၊ ဇန်နဝါရီ၊ ဖေဖော်ဝါရီ

* နွေရာသီ (Hot): မတ်၊ ဧပြီ၊ မေ

* မိုးရာသီ (Rainy): ဇွန်၊ ဇူလိုင်၊ သြဂုတ်၊ စက်တင်ဘာ၊ အောက်တိုဘာ

```typescript
export enum MyanmarSeason {

  COOL = 'cool',

  HOT = 'hot',

  RAINY = 'rainy',

}

export function getMyanmarSeason(month: number): MyanmarSeason {

  if (month === 10 || month === 11 || month === 0 || month === 1) {

    return MyanmarSeason.COOL;

  }

  if (month === 2 || month === 3 || month === 4) {

    return MyanmarSeason.HOT;

  }

  return MyanmarSeason.RAINY;

}
```

စမ်းကြည့်ရင်:

* `getMyanmarSeason(0)` (ဇန်နဝါရီလ) → `cool`
* `getMyanmarSeason(3)` (ဧပြီလ) → `hot`
* `getMyanmarSeason(6)` (ဇူလိုင်လ) → `rainy`

---

### 🛠️ Built With (အသုံးပြုထားသော နည်းပညာများ)

* **[React 18](https://react.dev/)** - Component-based UI Library

* **[TypeScript](https://www.typescriptlang.org/)** - Static Type Checking

* **[Vite](https://vitejs.dev/)** - Fast Frontend Build Tool

* **[Tailwind CSS](https://tailwindcss.com/)** - Utility-First CSS Framework

* **[shadcn/ui](https://ui.shadcn.com/)** - Accessible UI Components

* **[Framer Motion](https://www.framer.com/motion/)** - Smooth UI Animations

* **[Lucide Icons](https://lucide.dev/)** - Modern Clean Icons

* **[Vite PWA](https://vite-pwa-org.netlify.app/)** - Offline Support & Installable PWA

---

### 🚀 Getting Started (စတင်အသုံးပြုနည်း)

#### လိုအပ်ချက်များ (Prerequisites)

* [Node.js](https://nodejs.org/) (Version 18 သို့မဟုတ် အထက်)

* `npm` / `pnpm` / `yarn`

#### Installation Steps

၁။ Repository ကို Clone လုပ်ပါ:

```bash
git clone https://github.com/chit-hmue-than-thar/testing.git

cd testing
```

၂။ လိုအပ်တဲ့ Packages တွေကို Install လုပ်ပါ:

```bash
npm install
```

၃။ Development Server ကို Run ပါ:

```bash
npm run dev
```

၄။ Production Build လုပ်ချင်ရင်:

```bash
npm run build
```

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

<sub>Blending Myanmar tradition with modern technology • မြန်မာ့ရိုးရာယဉ်ကျေးမှုနှင့် ခေတ်မီနည်းပညာ ပေါင်းစပ်မှု 🇲🇲</sub>

</div>
