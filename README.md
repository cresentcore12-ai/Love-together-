# 💕 LoveTogether - Romantic Couple Streaming App

A premium, romantic web application for couples to watch Netflix, Spotify, YouTube together while seeing each other's faces in real-time.

## ✨ Features

### 🎬 Watch Anything Together
- **Netflix** - Screen share movies and shows
- **Spotify** - Listen to music together
- **YouTube** - Watch videos side by side
- One person shares, both enjoy - no duplicate subscriptions needed

### 📹 Always See Each Other
- Dual webcam display (stacked vertically on left)
- Real-time video feeds
- Cinematic main screen (right side fills entire space)
- Picture-in-picture style layout

### 💬 Stay Connected
- Live text chat
- Quick reaction buttons (💝😍😂🥰😢)
- Auto-responses for demo/testing

### 🔗 Private Rooms
- Unique shareable room links
- No signup required
- Just copy and share the link

### 💜 Shared Watchlist
- Save movies, shows, and songs
- Play YouTube songs directly
- Build your couple's collection

### 📞 Voice/Video Calling
- Integrated Jitsi Meet support
- Full audio/video calling
- No backend required

## 🚀 How to Use

### For Couples:

1. **Open the App**
   - One person opens `index.html` in their browser
   - Click "💕 Open Our Room"

2. **Share the Link**
   - Copy the private room link from the sidebar
   - Send it to your partner

3. **Start Streaming**
   - Click Netflix, Spotify, or YouTube to open in a new tab
   - Pick what you want to watch/listen to
   - Come back and click "🖥️ Screen Share"
   - Select the streaming tab
   - Both of you now see it together!

4. **Turn on Cameras**
   - Click the 📷 button to enable your webcam
   - Both faces appear on the left side
   - The content stays big on the right

5. **Enjoy!**
   - Chat, react, watch together
   - Your faces stay visible the whole time

## 📱 Connect With Us

**Social Handles:**
- 📷 Instagram: [@wav.rn](https://instagram.com/wav.rn)
- ☕ Buy Me a Coffee: [Nexus.io](https://buymeacoffee.com/Nexus.io)
- ✉️ Email: sociaro.io@gmail.com
- 🐦 Twitter: [@NahFel2n](https://twitter.com/NahFel2n)

**Support Us:** A social modal pops up when you first open the app and when closing, featuring a QR code for easy access!

## 🎨 Design Features

- **Premium Valentine's Theme** - Rose gradients, soft pink tones, romantic aesthetic
- **Cinematic Layout** - Left sidebar with webcams/controls, massive right screen
- **Floating Hearts** - Animated background particles
- **Glass Morphism** - Modern frosted glass UI elements
- **Custom Fonts** - Crimson Pro (serif) + DM Sans (sans-serif)
- **Smooth Animations** - Heartbeat effects, floating elements, transitions
- **Social Modal** - Beautiful pop-up with QR code on app start and close

## 🛠️ Technical Details

### Technologies Used
- Pure HTML5, CSS3, JavaScript (no frameworks)
- WebRTC for camera/screen sharing
- Jitsi Meet for video calling
- YouTube iframe API for embedded playback

### Browser Requirements
- Modern browser with WebRTC support
- Chrome, Firefox, Safari, Edge (latest versions)
- Camera/microphone permissions needed

### File Structure
```
lovetogether-app/
├── index.html          # Main application file (complete standalone app)
├── qr-code.jpg         # QR code image (replace with your own)
└── README.md          # This file
```

## 🎯 Customization

### Adding Your Own QR Code

The app currently has a placeholder QR code. To add your own:

1. Replace the QR code section in `index.html`:
   - Find the `<img src="data:image/svg+xml...` inside the `.qr-code` div
   - Replace with: `<img src="qr-code.jpg" alt="QR Code"/>`
   
2. Add your QR code image:
   - Save your QR code as `qr-code.jpg` in the same folder as `index.html`
   - Or use any image format and update the src accordingly

### Updating Social Links

All social links are in the HTML file in the social modal section. Update:
- Instagram: `@wav.rn`
- Buy Me a Coffee: `Nexus.io`
- Email: `sociaro.io@gmail.com`
- Twitter: `@NahFel2n`

## 📱 Responsive Design

- Desktop: Full cinematic experience with sidebar + main screen
- Tablet: Adjusted layout with horizontal scrolling
- Mobile: Vertical stacking, optimized controls

## 🔒 Privacy & Security

- **No Data Storage** - Everything runs in browser, nothing saved
- **No Servers** - Peer-to-peer connections via WebRTC
- **Private Rooms** - Unique hash-based room names
- **No Tracking** - No analytics, no cookies, no account required

## 🎯 Use Cases

- Long-distance couples watching movies together
- Date nights when apart
- Shared music listening sessions
- Watching concerts/shows together
- Just hanging out and seeing each other

## 🚧 Limitations

- Netflix/Spotify cannot be embedded directly (copyright restrictions)
  - Solution: Use screen share to stream content
- Screen share requires browser permissions
- Both users need the link to join the same room

## 💡 Tips

1. **Best Quality**: Use headphones to avoid echo
2. **Screen Share**: Make sure to share the tab, not entire screen
3. **Watchlist**: Add YouTube URLs for instant playback
4. **Reactions**: Use quick reaction buttons during funny/sweet moments
5. **Jitsi Call**: Open for full audio chat if screen share audio doesn't work

## 🎁 Perfect For

- Valentine's Day
- Anniversaries
- Long-distance relationships
- Quarantine date nights
- Any couple wanting to spend quality time together

## 📄 License

Free to use and modify. Built with 💕 for couples everywhere.

## 🤝 Support

- Follow us on social media (links in app)
- Support us via Buy Me a Coffee
- Email us for questions: sociaro.io@gmail.com

---

**Made with love 💕 by Nexus.io**

**Connect:**
- 📷 Instagram: @wav.rn
- ☕ Coffee: buymeacoffee.com/Nexus.io  
- 🐦 Twitter: @NahFel2n
- ✉️ Email: sociaro.io@gmail.com
