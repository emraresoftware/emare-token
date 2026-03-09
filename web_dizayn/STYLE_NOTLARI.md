# Emare Token — Tasarım Rehberi (Design System)

> Otomatik oluşturuldu: emarework Dervishi — Çeyiz Sistemi
> Ana Renk: `#ec4899`
> Tarih: 06 March 2026

---

## 1. RENK PALETİ (Brand Colors)

| Token | HEX | Kullanım |
|-------|-----|----------|
| `brand-50` | `#f9f4f7` | Çok açık arka plan, hover bg |
| `brand-100` | `#f5e9ef` | Açık arka plan |
| `brand-200` | `#eec8db` | Border (secondary buton) |
| `brand-300` | `#e791bc` | İkon accent |
| `brand-400` | `#e4579d` | Hover accent |
| `brand-500` | `#e7177e` | **Ana marka rengi (Primary)** |
| `brand-600` | `#c2146a` | Hover/active primary |
| `brand-700` | `#a00c55` | Koyu primary |
| `brand-800` | `#7a0941` | Koyu bg accent |
| `brand-900` | `#53082d` | Çok koyu bg |
| `brand-950` | `#2d0519` | En koyu bg (hero, footer) |

---

## 2. GRİ TONLARI

| Token | Kullanım |
|-------|----------|
| `white` | Sayfa arka planı, kart arka planı |
| `gray-100` | Border, divider |
| `gray-300` | Footer body text |
| `gray-500` | Kart açıklamaları |
| `gray-600` | Body paragraph text |
| `gray-800` | Varsayılan metin |
| `gray-900` | Başlıklar |
| `gray-950` | Footer arka plan |

---

## 3. EK RENKLER

| Renk | HEX | Kullanım |
|------|-----|----------|
| Success | `#22c55e` | Başarı, onay |
| Warning | `#f59e0b` | Uyarı |
| Error | `#ef4444` | Hata |
| Info | `#3b82f6` | Bilgi |

---

## 4. GRADYANLAR

### Primary Buton
```css
background: linear-gradient(to right, #e7177e, #a00c55);
```

### Gradient Text
```css
background: linear-gradient(135deg, #c2146a, #e4579d);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
```

### Hero Koyu Arka Plan
```css
background: linear-gradient(-45deg, #2d0519, #53082d, #7a0941);
```

---

## 5. TİPOGRAFİ

| Element | Font | Size | Weight |
|---------|------|------|--------|
| H1 | Inter | 3rem (48px) | 800 (ExtraBold) |
| H2 | Inter | 2.25rem (36px) | 700 (Bold) |
| H3 | Inter | 1.5rem (24px) | 600 (SemiBold) |
| Body | Inter | 1rem (16px) | 400 (Regular) |
| Small | Inter | 0.875rem (14px) | 400 |
| Button | Inter | 0.875rem (14px) | 600 |

---

## 6. SPACING

| Token | Değer | Kullanım |
|-------|-------|----------|
| xs | 4px | İkon-metin arası |
| sm | 8px | Küçük aralık |
| md | 16px | Kart padding |
| lg | 24px | Bölüm arası |
| xl | 48px | Büyük bölüm arası |
| 2xl | 96px | Hero section padding |

---

## 7. TAILWIND CONFIG

```javascript
tailwind.config = {
  theme: {
    extend: {
      fontFamily: { sans: ['Inter', 'system-ui', 'sans-serif'] },
      colors: {
        brand: {
          50: '#f9f4f7',
          100: '#f5e9ef',
          200: '#eec8db',
          300: '#e791bc',
          400: '#e4579d',
          500: '#e7177e',
          600: '#c2146a',
          700: '#a00c55',
          800: '#7a0941',
          900: '#53082d',
          950: '#2d0519',
        }
      }
    }
  }
}
```

---

*Otomatik oluşturuldu — emarework Dervishi Çeyiz Sistemi*
