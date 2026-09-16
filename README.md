# Micky's Publishing Kit v2.4.1

![Micky's](https://img.shields.io/badge/version-2.4.1-FF7A00?style=flat-square)
![License](https://img.shields.io/badge/licenses-7-7EC8E3?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-FF7A00?style=flat-square)

Professional publishing kit for mobile applications with comprehensive open source license support.

## ✨ Features

- **Orange (#FF7A00) & Light Blue (#7EC8E3) Branding** - Modern, cohesive design system
- **7 Open Source Licenses** - MIT, Apache 2.0, GPL v3, BSD 3-Clause, CC-BY, ISC, MPL 2.0
- **GitHub Pages Integration** - Auto-hosted license page at `https://opensource.mickys.app/`
- **Mobile Ready** - Responsive design for all devices
- **Google Play Compliant** - Meets open source attribution requirements
- **Easy Integration** - Copy-paste license screen code for Android & iOS

## 📦 What's Included

```
mickys/
├── docs/
│   ├── index.html              # License landing page
│   └── CNAME                   # Custom domain configuration
├── licenses/
│   ├── MIT.txt
│   ├── APACHE-2.0.txt
│   ├── GPL-3.0.txt
│   ├── BSD-3-CLAUSE.txt
│   ├── CC-BY-4.0.txt
│   ├── ISC.txt
│   └── MPL-2.0.txt
├── src/
│   ├── MickysLicenseScreen.kt  # Android License Screen
│   └── LicenseScreen.tsx       # iOS/React License Screen
└── assets/
    └── [icons & feature graphics]
```

## 🚀 Quick Start

### View Licenses
Visit **https://opensource.mickys.app/** to see the interactive license page with download buttons.

### Integrate into Your App

#### Android (Kotlin)
```kotlin
import com.mickys.MickysLicenseScreen

// In your activity
startActivity(Intent(this, MickysLicenseScreen::class.java))
```

#### iOS (React Native/Swift)
```tsx
import LicenseScreen from './LicenseScreen'

export default function App() {
  return <LicenseScreen />
}
```

## 📋 Licenses

This kit includes the following open source licenses:

| License | Type | Usage |
|---------|------|-------|
| MIT | Permissive | General dependencies |
| Apache 2.0 | Permissive | Build tools & frameworks |
| GPL v3 | Copyleft | Core libraries |
| BSD 3-Clause | Permissive | Networking libraries |
| Creative Commons BY | Attribution | Design assets |
| ISC | Permissive | Utilities |
| MPL 2.0 | File-based Copyleft | Compatibility libraries |

## 🌐 GitHub Pages Setup

This repository is configured for GitHub Pages with:

- **Source**: `/docs` folder on main branch
- **Custom Domain**: `opensource.mickys.app`
- **Status**: Auto-deployed on every push

### Enable Pages (if needed)
1. Go to **Settings** → **Pages**
2. Select **Deploy from a branch**
3. Choose **main** branch and `/docs` folder
4. Add custom domain: `opensource.mickys.app`

## 🎨 Color Scheme

- **Primary Orange**: `#FF7A00`
- **Secondary Blue**: `#7EC8E3`
- **Light Gray**: `#f5f5f5`
- **Dark Text**: `#333333`

## ✅ Google Play Compliance

This kit satisfies Google Play's open source license requirements:

✓ All 7 licenses clearly listed  
✓ Downloadable license texts  
✓ Publicly accessible via dedicated URL  
✓ In-app license screen integration  
✓ 3-year attribution requirement met via GitHub Pages  

Link in your app: `https://opensource.mickys.app/`

## 📝 File Structure

### License Screens
- `src/MickysLicenseScreen.kt` - Native Android implementation
- `src/LicenseScreen.tsx` - React/iOS implementation

### Configuration
- `docs/CNAME` - Custom domain pointer for GitHub Pages
- `docs/index.html` - Landing page with license cards

### Licenses
- `licenses/` - Individual license text files (downloadable)

## 🔧 Customization

All colors can be customized:

1. Edit `docs/index.html` to change:
   ```html
   background: linear-gradient(135deg, #FF7A00 0%, #7EC8E3 100%);
   ```

2. Update `src/MickysLicenseScreen.kt` UI colors
3. Modify `src/LicenseScreen.tsx` theme variables

## 📞 Support

For questions or issues:
- Check the [GitHub Issues](https://github.com/mporuban863-source/mickys/issues)
- Review license terms at [Open Source Initiative](https://opensource.org/licenses/)

## 📄 License

Micky's Publishing Kit itself is provided as a reference implementation.  
All included licenses apply to their respective projects and dependencies.

---

**Micky's v2.4.1** | [View Licenses](https://opensource.mickys.app/) | Built with ❤️
