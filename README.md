# Burma Calendar (မြန်မာပြက္ခဒိန်)

![Burma Calendar Preview](./public/social-preview.png)

> **Summary**  
> လနှင့် ခုနှစ်ကို ရွေးချယ်မယ် -> အင်္ဂလိပ်ရက်စွဲနှင့် မြန်မာသက္ကရာဇ်/မြန်မာလများကို တွက်ချက်ပြသမယ် -> သက်ဆိုင်ရာ အစိုးရရုံးပိတ်ရက်များနှင့် ၃ လတာ အားလပ်ရက်စာရင်းကို ချိတ်ဆက်ပြသမယ် -> မြန်မာ့ရာသီ ၃ မျိုး (ဆောင်း၊ နွေ၊ မိုး) အလိုက် Seasonal Theming စနစ်ဖြင့် ခေတ်မီလှပစွာ ပုံဖော်ပြသမယ်။

---

## 📖 အချက်အလက်နှင့် အကိုးအကားများ (Data & References)

1. **မြန်မာသက္ကရာဇ်နှင့် ပြက္ခဒိန်တွက်ချက်မှု (Myanmar Calendar & Era Calculation)**:
   - မြန်မာသက္ကရာဇ် တွက်ချက်မှု (သင်္ကြန်အကူးအပြောင်းလအလိုက် ၁၃၈၅/၁၃၈၆ စသည်) နှင့် မြန်မာလတွဲများ (ဥပမာ - နတ်တော်/ပြာသို၊ တပို့တွဲ/တပေါင်း) ကို စနစ်တကျ ထည့်သွင်းတွက်ချက်ထားပါသည်။
2. **အစိုးရရုံးပိတ်ရက်များ (Myanmar Public Holidays)**:
   - ပြည်ထောင်စုသမ္မတမြန်မာနိုင်ငံတော် အစိုးရရုံးပိတ်ရက်များ အပြန်တမ်းကို အခြေခံထားပြီး ဒေတာများကို [`src/data/holidays.json`](./src/data/holidays.json) တွင် စုစည်းသိမ်းဆည်းထားပါသည်။
3. **ရာသီဥတုအလိုက် အရောင်စနစ် (Myanmar Seasonal Theming)**:
   - မြန်မာ့ရိုးရာ ရာသီ ၃ မျိုး (ဆောင်းရာသီ၊ နွေရာသီ၊ မိုးရာသီ) အလိုက် သဘာဝဆန်ပြီး မျက်စိအေးချမ်းစေမည့် Color Palettes များကို အလိုအလျောက် သတ်မှတ်ပေးပါသည်။

---

## 🌟 အဓိကလုပ်ဆောင်ချက်များ (Features & Procedure Steps)

1. **ခုနှစ်နှင့် လ ရွေးချယ်နိုင်ခြင်း (Month & Year Selector)**
   - ၂၀၂၄၊ ၂၀၂၅၊ ၂၀၂၆၊ ၂၀၂၇ စသည့် ခုနှစ်များနှင့် လ ၁၂ လကို Dropdown သို့မဟုတ် Next / Previous ခလုတ်များဖြင့် လွယ်ကူစွာ ရွေးချယ်ကြည့်ရှုနိုင်ပါသည်။
   - **"ဒီနေ့ (Today)"** ခလုတ်ကို နှိပ်လိုက်ရုံဖြင့် လက်ရှိရောက်ရှိနေသော လနှင့် ရက်စွဲသို့ ချက်ချင်း ပြန်လည်ရောက်ရှိစေပါသည်။

2. **ပြက္ခဒိန်ဇယား ဖော်ပြခြင်း (Calendar Grid Layout)**
   - တနင်္ဂနွေမှ စနေနေ့အထိ ၇ ရက်ပြက္ခဒိန် Grid တွင် အင်္ဂလိပ်ရက်စွဲ (Gregorian Date) နှင့် မြန်မာဂဏန်းရက်စွဲများကို တွဲဖက်ဖော်ပြပေးပါသည်။
   - စနေ၊ တနင်္ဂနွေ (Weekend) ရက်များ၊ ယနေ့ရက် (Today) နှင့် ရုံးပိတ်ရက် (Holiday) များကို အရောင်ခွဲခြားကာ ထင်ရှားစွာ ပြသပေးပါသည်။

3. **မြန်မာသက္ကရာဇ်နှင့် လတွဲများ (Myanmar Era & Month Pairs)**
   - Header တွင် ရွေးချယ်ထားသောလအလိုက် သက်ဆိုင်သည့် **မြန်မာသက္ကရာဇ် (ဥပမာ - သက္ကရာဇ်-၁၃၈၆ ခု)** နှင့် **မြန်မာလတွဲ (ဥပမာ - တပေါင်း / တန်ခူး)** ကို အလိုအလျောက် တွက်ချက်ဖော်ပြပါသည်။

4. **၃ လတာ အားလပ်ရက်စာရင်း (3-Month Holiday Overview Sidebar)**
   - လက်ရှိလ အပါအဝင် နောက်လာမည့် ၂ လ (စုစုပေါင်း ၃ လတာ) အတွက် အစိုးရရုံးပိတ်ရက် စုစုပေါင်း အရေအတွက်နှင့် အားလပ်ရက်အမည်များကို Sidebar တွင် ရှင်းလင်းစွာ စာရင်းပြုစု ပြသပေးပါသည်။

5. **မြန်မာ့ရာသီအလိုက် Theme ပြောင်းလဲခြင်း (Seasonal Adaptive UI)**
   - မြန်မာနိုင်ငံ၏ ရာသီဥတု ၃ မျိုးပေါ်မူတည်၍ UI Theme သည် အလိုအလျောက် ပြောင်းလဲပေးပါသည်:
     - ❄️ **ဆောင်းရာသီ (Cool Season - နိုဝင်ဘာ မှ ဖေဖော်ဝါရီ)**: Cool & Crisp (အပြာရောင်အေးအေးလေး)
     - ☀️ **နွေရာသီ (Hot Season - မတ် မှ မေ)**: Warm & Energetic (နွေးထွေးသော ရွှေဝါ/လိမ္မော်ရောင်)
     - 🌧️ **မိုးရာသီ (Rainy Season - ဇွန် မှ အောက်တိုဘာ)**: Lush & Calm (စိမ်းလန်းစိုပြေသော မြစိမ်းရောင်)
   - Dark Mode နှင့် Light Mode နှစ်မျိုးစလုံးတွင် အလိုက်သင့် ပြောင်းလဲအသုံးပြုနိုင်ပါသည်။

6. **PWA (Progressive Web App) & Offline အသုံးပြုနိုင်ခြင်း**
   - ဖုန်းနှင့် Desktop များတွင် Native App တစ်ခုကဲ့သို့ Install ပြုလုပ်နိုင်ပြီး အင်တာနက်လိုင်းမရှိချိန် (Offline) တွင်လည်း ပြက္ခဒိန်ကို အဆင်ပြေစွာ ဖွင့်ကြည့်နိုင်ပါသည်။

---

## 🗂️ Data Structure (ဒေတာဖွဲ့စည်းပုံ)

ရုံးပိတ်ရက်ဒေတာများကို Junior Developer များ နားလည်လွယ်စေရန်နှင့် အလွယ်တကူ ထပ်မံဖြည့်စွက်နိုင်ရန် အောက်ပါ JSON Structure အတိုင်း တည်ဆောက်ထားပါသည်:

```json
{
  "years": {
    "2025": {
      "year": 2025,
      "holidays": [
        {
          "month": "January",
          "name": "လွတ်လပ်ရေးနေ့",
          "dates": ["4"],
          "total_days": 1
        },
        {
          "month": "February",
          "name": "ပြည်ထောင်စုနေ့",
          "dates": ["12"],
          "total_days": 1
        },
        {
          "month": "April",
          "name": "မဟာသင်္ကြန် ရုံးပိတ်ရက်များ",
          "dates": ["13", "14", "15", "16", "17"],
          "total_days": 5
        }
      ]
    }
  }
}
```

---

## 💻 Logic & Implementation (တွက်ချက်မှုဆိုင်ရာ Code နမူနာများ)

### ၁။ အင်္ဂလိပ်ဂဏန်းမှ မြန်မာဂဏန်းသို့ ပြောင်းလဲခြင်း (Myanmar Numerals Conversion)
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

// နမူနာ အသုံးပြုပုံ
console.log(toMyanmarNumerals(2025)); // "၂၀၂၅"
```

### ၂။ မြန်မာသက္ကရာဇ် တွက်ချက်ခြင်း (Myanmar Era Calculation)
```typescript
export function getMyanmarEraLabel(date: Date): string {
  const year = date.getFullYear();
  const month = date.getMonth(); // 0 = January, 3 = April

  // သင်္ကြန်ကာလ (ဧပြီလ) တွင် သက္ကရာဇ် ၂ ခု ကူးပြောင်းချိန်
  if (month === 3) {
    return `${toMyanmarNumerals(year - 639)} / ${toMyanmarNumerals(year - 638)}`;
  }

  return toMyanmarNumerals(year - (month < 3 ? 639 : 638));
}

// နမူနာ အသုံးပြုပုံ
console.log(getMyanmarEraLabel(new Date(2025, 0, 1))); // "၁၃၈၆"
```

### ၃။ မြန်မာ့ရာသီ ၃ မျိုး ခွဲခြားတွက်ချက်ခြင်း (Myanmar Season Logic)
```typescript
export enum MyanmarSeason {
  COOL = 'cool',   // ဆောင်းရာသီ
  HOT = 'hot',     // နွေရာသီ
  RAINY = 'rainy', // မိုးရာသီ
}

export function getMyanmarSeason(month: number): MyanmarSeason {
  // နိုဝင်ဘာ (10)၊ ဒီဇင်ဘာ (11)၊ ဇန်နဝါရီ (0)၊ ဖေဖော်ဝါရီ (1) -> ဆောင်းရာသီ
  if (month === 10 || month === 11 || month === 0 || month === 1) {
    return MyanmarSeason.COOL;
  }
  // မတ် (2)၊ ဧပြီ (3)၊ မေ (4) -> နွေရာသီ
  if (month === 2 || month === 3 || month === 4) {
    return MyanmarSeason.HOT;
  }
  // ဇွန် (5) မှ အောက်တိုဘာ (9) -> မိုးရာသီ
  return MyanmarSeason.RAINY;
}
```

---

## 🛠️ Built With (အသုံးပြုထားသော နည်းပညာများ)

- **[React 18](https://react.dev/)** - Modern Component-driven UI
- **[TypeScript](https://www.typescriptlang.org/)** - Type Safety & Developer Experience
- **[Vite](https://vitejs.dev/)** - Next Generation Frontend Tooling
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS Styling
- **[shadcn/ui](https://ui.shadcn.com/)** - Accessible & Beautiful Components
- **[Framer Motion](https://www.framer.com/motion/)** - Smooth Animations & Transitions
- **[Lucide Icons](https://lucide.dev/)** - Modern Minimalist Icons
- **[Vite PWA](https://vite-pwa-org.netlify.app/)** - Offline & Installable Web App

---

## 🚀 Getting Started (စတင်အသုံးပြုပုံ)

### လိုအပ်ချက်များ (Prerequisites)
- [Node.js](https://nodejs.org/) (Version 18 သို့မဟုတ် အထက်)
- `npm` သို့မဟုတ် `pnpm` / `yarn`

### စတင် Run နည်း (Installation Steps)

1. **Repository ကို Clone ပြုလုပ်ပါ**:
   ```bash
   git clone https://github.com/chit-hmue-than-thar/burma-calendar.git
   cd burma-calendar
   ```

2. **Dependencies များကို Install ပြုလုပ်ပါ**:
   ```bash
   npm install
   ```

3. **Development Server ကို စတင် Run ပါ**:
   ```bash
   npm run dev
   ```

4. **Production Build ပြုလုပ်ရန်**:
   ```bash
   npm run build
   ```

---

## 👥 Contributors & Participants

<table>
  <thead>
    <tr>
      <th colspan="4">Contributors</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/sannlynnhtun-coding">
          <img src="https://github.com/sannlynnhtun-coding.png" width="80px;" alt="sannlynnhtun-coding"/><br />
          <sub><b>sannlynnhtun-coding</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/yokesann">
          <img src="https://github.com/yokesann.png" width="80px;" alt="yokesann"/><br />
          <sub><b>yokesann</b></sub>
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <sub>Blending tradition with technology • မြန်မာ့ရိုးရာယဉ်ကျေးမှုနှင့် ခေတ်မီနည်းပညာ ပေါင်းစပ်မှု 🇲🇲</sub>
</div>
