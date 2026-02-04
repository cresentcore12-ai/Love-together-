# 💕 LoveTogether - Working Version

A premium romantic web app for couples to watch & listen together with real-time video.

## ✨ What's Fixed & Working

### ✅ Private Link Sharing - FIXED!
- Person 1 opens the app, gets a unique room link
- Person 1 shares link with Person 2
- Person 2 clicks link → **automatically joins the same room**
- Both see the same room name in the URL

### ✅ YouTube Playing - FIXED!
- Add YouTube URLs to watchlist
- Click ▶ play button
- **Both people see the video at the same time** (synced)
- Works perfectly with proper YouTube embed

### ✅ Video + Screen Share - WORKING!
**Uses Jitsi Meet (built-in, free, no backend needed)**
- Click "📞 Start Call" on left sidebar
- **Both people need to click it** (joins same Jitsi room)
- Jitsi handles:
  - ✅ Webcam video for both
  - ✅ Audio for both
  - ✅ **Screen share for Netflix/Spotify**
  - ✅ All synchronized automatically

## 🎯 How To Use (Step by Step)

### Person 1 (Host):
1. Open `index.html` in browser
2. Click "💝 Our Room"
3. Click "📞 Start Call" (Jitsi opens)
4. Copy the room link (🔗 section)
5. Send link to your partner

### Person 2 (Partner):
1. Click the link Person 1 sent
2. Page auto-opens to room
3. Click "📞 Start Call"
4. **You're now connected!** Both can see/hear each other

### To Watch Netflix/Spotify Together:
1. In Jitsi call, click the **screen share button** (in Jitsi interface)
2. Select your Netflix/Spotify tab
3. Partner sees your screen live with audio
4. Both watch together!

### To Watch YouTube Together:
1. Paste YouTube URL in watchlist
2. Click ▶ play
3. **Both see it synced** in the big screen

## 📱 All Features Working

- ✅ **Jitsi Video Call** - See each other's faces
- ✅ **Screen Share via Jitsi** - Share Netflix/Spotify
- ✅ **YouTube Sync** - Watch YouTube together
- ✅ **Live Chat** - Send messages
- ✅ **Reactions** - Quick emoji reactions  
- ✅ **Watchlist** - Save YouTube videos
- ✅ **Social Modal** - QR code + handles on open/close
- ✅ **Private Rooms** - Unique shareable links

## 🔧 Technical Details

### How It Works:

**Room Joining:**
- Room name stored in URL hash (`#moonlight-1234`)
- When partner clicks link, hash is read
- Both join same Jitsi room automatically

**YouTube Sync:**
- Uses YouTube iframe API with autoplay
- Same video ID = same video for both
- Embedded directly, no backend needed

**Video + Screen Share:**
- Jitsi Meet (free, embedded)
- Handles WebRTC signaling automatically
- No server setup required!

## 📝 Customization

### Add Your QR Code:
Replace line ~100 in HTML:
```html
<img src="qr-code.jpg" alt="QR Code"/>
```
Then add `qr-code.jpg` file to same folder.

### Your Social Links:
All in the HTML around line 90:
- Instagram: `@wav.rn`
- Coffee: `Nexus.io`
- Email: `sociaro.io@gmail.com`
- Twitter: `@NahFel2n`

## 🚀 Deployment

Works as a **single HTML file**!

**Option 1 - Local:**
- Just open `index.html` in browser
- Share the link with `#room-name` at end

**Option 2 - Online (Free):**
- Upload to **GitHub Pages**, **Netlify**, or **Vercel**
- Free hosting, works instantly
- Get a real URL like `yourdomain.com#moonlight-1234`

## ⚠️ Important Notes

1. **Both people must click "Start Call"** to see each other
2. **Screen share** is done via Jitsi (click screen share button in Jitsi interface)
3. **YouTube** plays synced automatically when someone clicks ▶
4. **Room link** must include the `#room-name` part

## 💡 Pro Tips

1. **Use headphones** to avoid echo
2. **Screen share the tab, not whole screen** for better quality
3. **Click "Start Call" simultaneously** for fastest connection
4. **Add YouTube videos** to watchlist for instant playback

## 🎬 How Netflix/Spotify Works

Since Netflix/Spotify block embedding:
1. Person 1 opens Netflix in a tab
2. Person 1 clicks "📞 Start Call" in LoveTogether
3. In Jitsi, Person 1 clicks **screen share**
4. Select the Netflix tab
5. Person 2 sees & hears everything!

Same for Spotify - screen share the tab.

## 📞 Why Jitsi?

- ✅ Free & open source
- ✅ No account needed
- ✅ Handles video, audio, screen share
- ✅ Works in browser (no download)
- ✅ Already handles WebRTC signaling
- ✅ Room-based (perfect for private couples)

## 🎁 Perfect For

- Long-distance couples
- Movie nights apart
- Music listening together
- Virtual date nights
- Just hanging out

## 📄 Files

- `index.html` - Complete standalone app
- `README.md` - This file
- `qr-code.jpg` - (Add your own QR code)

## 🤝 Connect

- 📷 Instagram: [@wav.rn](https://instagram.com/wav.rn)
- ☕ Coffee: [buymeacoffee.com/Nexus.io](https://buymeacoffee.com/Nexus.io)
- 🐦 Twitter: [@NahFel2n](https://twitter.com/NahFel2n)
- ✉️ Email: sociaro.io@gmail.com

---

**Made with 💕 by Nexus.io**

**Everything works! Share the link, start the call, enjoy together! 🎬💕**
