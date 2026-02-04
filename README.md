# 💕 LoveTogether - Browse Anything Together

Full web browser with webcams + Google search for couples!

## ✨ Features

### 🌐 Full Web Browser
- **Google search bar** - Search anything or enter URLs
- **Quick links** - Netflix, Spotify, YouTube buttons
- **Browser controls** - Back, forward, refresh, home
- **Any website** - Try to browse any site together

### 📹 Picture-in-Picture Webcams
- **Always visible** - Webcams float over the browser
- **Both faces** - See each other while browsing
- **Hover controls** - Mic and camera toggles
- **Compact design** - Doesn't block the content

### 💬 Live Features
- **Chat** - Message each other while browsing
- **Room link** - Share one link, join same session
- **Jitsi integration** - Full video call + screen share

## ⚠️ IMPORTANT: Website Embedding Limitations

### What Works ✅
- **YouTube** - Plays perfectly
- **Google Search** - Works great
- **Wikipedia** - Full access
- **Most blogs/news sites** - Usually work
- **Simple websites** - Generally embed fine

### What Doesn't Work ❌
**Netflix, Spotify, Hulu, Disney+, Prime Video** - These sites **block iframe embedding** due to security policies (X-Frame-Options header).

### 💡 THE SOLUTION: Use Jitsi for Everything!

**For Netflix/Spotify/Protected sites:**

1. Click **"📞 Open Jitsi Call"** button (in side panel)
2. **Both people** join the Jitsi call
3. In Jitsi, click **"Share Screen"**
4. Select your Netflix/Spotify tab
5. **Partner sees & hears everything!**

This works because:
- ✅ Jitsi handles real WebRTC peer-to-peer
- ✅ Screen share captures everything (even protected sites)
- ✅ Audio is included
- ✅ Both webcams visible
- ✅ No embedding needed

## 🎯 Best Usage Guide

### Option 1: YouTube & Simple Sites
- Use the **built-in browser** for YouTube, Google, Wikipedia
- Webcams stay visible
- Both see the same sites

### Option 2: Netflix/Spotify/Protected Sites
1. Click **"📞 Open Jitsi Call"**
2. Both join Jitsi
3. Use **Jitsi's screen share** for Netflix/Spotify
4. Chat in LoveTogether or Jitsi

### Option 3: Hybrid Approach
- Keep **LoveTogether open** for chat + room management
- Open **Jitsi in another tab** for video + screen share
- Best of both worlds!

## 🚀 How To Use

**Person 1:**
1. Open `index.html`
2. Click "🌐 Browse Together"
3. Copy room link (side panel)
4. Send to Person 2
5. Start browsing or click "Open Jitsi Call"

**Person 2:**
1. Click the link Person 1 sent
2. Joins same room automatically
3. Click "Open Jitsi Call" to connect

## 📱 Features Breakdown

### Built-in Browser:
- Google search
- Direct URL entry
- Quick links (Netflix, Spotify, YouTube buttons)
- Note: Many sites block embedding

### Webcams:
- Picture-in-picture overlay
- Toggle camera on/off
- Toggle mic on/off
- Compact floating design

### Chat:
- Live messaging
- Auto-replies for testing
- Side panel (collapsible)

### Jitsi Integration:
- Opens in new tab
- Same room name
- Video + audio + screen share
- Works for ALL websites

## 🛠️ Technical Details

### Why Sites Block Embedding:

Websites use `X-Frame-Options` or `Content-Security-Policy` headers to prevent being loaded in iframes. This is for security (prevents clickjacking attacks).

**Sites that block:**
- Netflix
- Spotify  
- Hulu
- Disney+
- Most streaming services
- Banking sites
- Many social media sites

**Sites that allow:**
- YouTube (explicitly allows embedding)
- Wikipedia
- Most news sites
- Personal blogs
- Public content sites

### How Jitsi Solves This:

Jitsi's **screen share** captures your actual screen/tab, so:
- ✅ No embedding needed
- ✅ Shows literally anything on your screen
- ✅ Includes audio
- ✅ Real-time streaming

## 🎬 Recommended Workflow

**For YouTube:**
```
Use built-in browser → Search YouTube → Both watch together
```

**For Netflix/Spotify:**
```
Open Jitsi Call → Screen share Netflix tab → Both watch together
```

**For General Browsing:**
```
Built-in browser works for most sites
Jitsi screen share for protected sites
```

## 📝 Customization

### Add Your QR Code:
Replace the `<img src="data:image/svg+xml...` in the social modal section with:
```html
<img src="qr-code.jpg" alt="QR Code"/>
```

### Social Links:
All around line 150-200:
- Instagram: `@wav.rn`
- Coffee: `Nexus.io`
- Email: `sociaro.io@gmail.com`
- Twitter: `@NahFel2n`

## 💡 Pro Tips

1. **For best experience**: Use Jitsi for video call + Netflix screen share, keep LoveTogether for chat
2. **YouTube works great**: Use the built-in browser for YouTube
3. **Quick links**: Click Netflix/Spotify buttons to try (if blocked, use Jitsi screen share)
4. **Mobile**: Works on mobile but Jitsi in separate tab works better
5. **Share link**: Always include the `#room-name` part

## 🎁 What You Get

- ✅ Google search bar
- ✅ Web browser interface  
- ✅ Picture-in-picture webcams
- ✅ Live chat
- ✅ Quick site buttons
- ✅ Jitsi integration (full solution)
- ✅ Social modal with QR code
- ✅ Private room links
- ✅ Beautiful romantic UI

## 📞 Connect

- 📷 Instagram: [@wav.rn](https://instagram.com/wav.rn)
- ☕ Coffee: [buymeacoffee.com/Nexus.io](https://buymeacoffee.com/Nexus.io)
- 🐦 Twitter: [@NahFel2n](https://twitter.com/NahFel2n)
- ✉️ Email: sociaro.io@gmail.com

---

**Made with 💕 by Nexus.io**

**TL;DR: Built-in browser for YouTube/Google, Jitsi screen share for Netflix/Spotify. Best of both worlds! 🌐💕**
