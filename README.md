<div align="center">

<img src="https://beemusic.vncore.net/img/bee.png" alt="BeeMusic Logo" width="320" />

# 🐝 BeeMusic — Trải Nghiệm Âm Nhạc Đỉnh Cao Trên Discord

**Bot phát nhạc chất lượng cao, mượt mà, không delay dành cho cộng đồng Discord của bạn.**

[![Discord](https://img.shields.io/badge/Server%20H%E1%BB%97%20Tr%E1%BB%A3-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://beemusic.vncore.net/discord)
[![Website](https://img.shields.io/badge/Trang%20Ch%E1%BB%A7-beemusic.vncore.net-ffb300?style=for-the-badge&logo=googlechrome&logoColor=white)](https://beemusic.vncore.net)
[![Invite](https://img.shields.io/badge/Th%C3%AAm%20Bot-Invite%20BeeGold-green?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1512007881543913552&permissions=2150754416&scope=bot+applications.commands)

[🇻🇳 Tiếng Việt](#-tiếng-viet) | [🇬🇧 English](#-english)

</div>

---

# 🇻🇳 Tiếng Việt

Chào mừng bạn đến với **BeeMusic**! Đây là hệ thống bot phát nhạc chuyên nghiệp, giúp nâng tầm kết nối cộng đồng của bạn thông qua những giai điệu chất lượng cao hoàn toàn miễn phí.

## 🌟 Tại sao nên chọn BeeMusic?

- 🎵 **Kho Nhạc Không Giới Hạn** — Phát nhạc mượt mà từ **YouTube, Spotify, SoundCloud, Apple Music** và nhiều nền tảng khác.
- 🔊 **Âm Thanh Cực Đỉnh** — Hỗ trợ âm thanh chuẩn **192kbps** (Miễn phí) và lên tới **320kbps HIFI** (Premium) mang lại trải nghiệm nghe nhạc chân thực nhất.
- 🎛️ **Bộ Lọc Âm Thanh Đa Dạng** — Tự do thay đổi hiệu ứng nhạc theo sở thích: *Bassboost, 8D, Nightcore, Vaporwave, Karaoke, v.v.*
- 🎮 **Bảng Điều Khiển Trực Quan (Setup Panel)** — Tạo riêng một kênh nghe nhạc với giao diện nút bấm tiện lợi. Bạn chỉ cần nhấn nút để Dừng, Phát, Bỏ qua hoặc Tăng/Giảm âm lượng mà không cần gõ lệnh.
- 🤖 **Hệ Thống Đa Bot (Multi-Bot)** — Sở hữu bộ ba bot **BeeGold** (Bot chính), **BeeBlue** và **BeePink** giúp phát nhạc song song tại nhiều phòng voice cùng lúc.
- 📡 **Chế Độ Treo Kênh 24/7** — Giữ bot luôn túc trực trong kênh thoại kể cả khi hết nhạc để sẵn sàng phát bài tiếp theo (`/247`).
- 🔁 **Tự Động Phát Nhạc (Autoplay)** — Tự động tìm kiếm và phát các bài hát tương tự khi danh sách chờ kết thúc.
- 📝 **Danh Sách Nhạc Cá Nhân** — Lưu lại những bài hát yêu thích để phát lại nhanh chóng bất cứ lúc nào.
- 🇻🇳🇺🇸 **Hỗ Trợ Song Ngữ** — Giao diện hiển thị tiếng Việt và tiếng Anh thân thiện, dễ sử dụng.

---

## 🎮 Danh Sách Lệnh Đầy Đủ (42 Lệnh)

BeeMusic sử dụng hệ thống lệnh Slash (`/`) trực quan và nhanh chóng. Dưới đây là danh sách toàn bộ các lệnh được chia theo nhóm tính năng:

<details>
<summary>🎵 <b>1. Nhóm Lệnh Phát Nhạc (Playback - 23 lệnh)</b></summary>

| Lệnh | Mô Tả |
|------|-------|
| `/play <tên / link>` | Tìm kiếm và phát nhạc từ YouTube, Spotify, SoundCloud, Apple Music... |
| `/pause` | Tạm dừng bài hát đang phát |
| `/resume` | Tiếp tục phát bài hát đang bị tạm dừng |
| `/skip` | Bỏ qua bài hát hiện tại để phát bài tiếp theo |
| `/stop` | Dừng phát nhạc, xóa sạch hàng chờ và rời kênh thoại |
| `/queue` | Xem danh sách các bài hát trong hàng chờ |
| `/nowplaying` | Hiển thị bài hát đang phát cùng tiến trình chi tiết |
| `/volume <0-150>` | Điều chỉnh âm lượng bot (Bronze tối đa 120%, Silver+ tối đa 150%) |
| `/join` | Yêu cầu bot tham gia vào kênh thoại của bạn |
| `/leave` | Ngắt kết nối bot ra khỏi kênh thoại |
| `/loop <off/track/queue>` | Bật/tắt chế độ lặp lại bài hát hiện tại hoặc cả hàng chờ |
| `/shuffle` | Trộn ngẫu nhiên thứ tự các bài hát trong hàng chờ |
| `/seek <thời gian>` | Tua nhanh tới vị trí mong muốn (ví dụ: `1m30s`, `45s`) |
| `/forward <giây>` | Tua nhanh bài hát lên phía trước một khoảng thời gian |
| `/rewind <giây>` | Tua ngược bài hát về phía sau một khoảng thời gian |
| `/lyrics [tên bài]` | Tìm kiếm lời của bài hát đang phát hoặc một bài hát bất kỳ |
| `/jump <vị trí>` | Nhảy trực tiếp đến số thứ tự bài hát được chỉ định trong hàng chờ |
| `/previous` | Phát lại bài hát vừa chạy xong trước đó |
| `/replay` | Phát lại bài hát hiện tại từ đầu |
| `/grab` | Gửi thông tin chi tiết bài hát đang phát vào tin nhắn riêng (DM) |
| `/clearqueue` | Xóa sạch toàn bộ bài hát trong hàng chờ |
| `/remove <vị trí>` | Xóa một bài hát cụ thể khỏi hàng chờ theo số thứ tự |
| `/removedups` | Quét và loại bỏ tất cả bài hát bị trùng lặp trong hàng chờ |

</details>

<details>
<summary>🎛️ <b>2. Nhóm Bộ Lọc Âm Thanh (Audio Filters - 10 lệnh)</b></summary>

| Lệnh | Mô Tả |
|------|-------|
| `/8d` | Áp dụng bộ lọc hiệu ứng âm thanh vòm 8D xoay vòng |
| `/bassboost <low/medium/high>` | Tăng cường âm trầm (Bass) với các mức độ khác nhau |
| `/clearfilter` | Gỡ bỏ toàn bộ hiệu ứng âm thanh đang áp dụng |
| `/karaoke` | Lọc bỏ giọng hát ca sĩ để chỉ phát nhạc nền (Instrumental) |
| `/lofi` | Áp dụng hiệu ứng âm thanh Lofi ấm áp và chill |
| `/lowpass` | Áp dụng bộ lọc cắt tần số cao Lowpass |
| `/nightcore` | Tăng tốc độ nhạc (tempo) và nâng tông giọng (pitch) |
| `/slowmode` | Làm chậm nhịp điệu và tempo của bài hát |
| `/timescale` | Tự do điều chỉnh tốc độ (speed) và âm vực (pitch) của bài nhạc |
| `/vaporwave` | Áp dụng hiệu ứng làm chậm và kéo dãn âm thanh độc đáo |

</details>

<details>
<summary>📝 <b>3. Nhóm Lệnh Playlist (1 lệnh)</b></summary>

| Lệnh | Mô Tả |
|------|-------|
| `/playlist` | Quản lý danh sách nhạc cá nhân (Tạo, xóa, thêm bài, phát playlist) |

</details>

<details>
<summary>⚙️ <b>4. Nhóm Lệnh Cài Đặt (Settings - 4 lệnh)</b></summary>

| Lệnh | Mô Tả |
|------|-------|
| `/247` | Bật/tắt chế độ treo bot 24/7 trong kênh thoại (yêu cầu gói Silver trở lên) |
| `/setup` | Tạo kênh yêu cầu nhạc tĩnh kèm bảng điều khiển nút bấm trực quan (Admin) |
| `/premium` | Xem thông tin gói và kích hoạt/hủy kích hoạt Premium cho server |
| `/language` | Cấu hình ngôn ngữ hiển thị và phản hồi của bot (Tiếng Việt / English) |

</details>

<details>
<summary>🛠️ <b>5. Nhóm Lệnh Tiện Ích (Utility - 4 lệnh)</b></summary>

| Lệnh | Mô Tả |
|------|-------|
| `/ping` | Kiểm tra độ trễ kết nối của bot đến Discord và máy chủ âm thanh |
| `/help` | Hiển thị menu hướng dẫn sử dụng và trợ giúp nhanh |
| `/invite` | Lấy liên kết mời các phiên bản bot BeeMusic vào server của bạn |
| `/sleeptimer <phút>` | Hẹn giờ tự động tắt nhạc và rời phòng voice sau X phút |

</details>

---

## 💎 Gói Premium Có Gì Đặc Biệt?

Nâng cấp lên **BeeMusic Premium** để mở khóa toàn bộ sức mạnh của bot:
- ⚡ **Chất lượng âm thanh 320kbps HIFI** chuẩn phòng thu.
- 🎛️ Mở khóa toàn bộ **bộ lọc âm thanh cao cấp** (Bassboost cực mạnh, hiệu ứng 8D...).
- 🔁 Không giới hạn số lượng bài hát lưu trong danh sách cá nhân.
- 👑 **Kích hoạt Premium cho toàn bộ máy chủ** (tất cả thành viên đều được dùng ké).
- 🎨 Tùy biến Avatar & Tên của bot theo phong cách riêng của server bạn.
- 🚀 Băng thông phát nhạc ưu tiên cao nhất, không lo giật lag.

👉 Nâng cấp ngay tại: [beemusic.vncore.net](https://beemusic.vncore.net/)

---

## 📞 Hỗ Trợ Kỹ Thuật

Nếu bạn gặp bất kỳ khó khăn nào trong quá trình sử dụng hoặc muốn đóng góp ý kiến:
- **Server Discord Hỗ Trợ:** [Tham gia tại đây (discord)](https://discord.gg/WfQmNFSAcq)
- **Trang chủ:** [beemusic.vncore.net](https://beemusic.vncore.net)
- **Email liên hệ:** support@vncore.net

---

# 🇬🇧 English

Welcome to **BeeMusic**! A professional Discord music bot system designed to elevate your community through high-quality music streaming entirely for free.

## 🌟 Why Choose BeeMusic?

- 🎵 **Unlimited Music Catalog** — Stream seamlessly from **YouTube, Spotify, SoundCloud, Apple Music**, and many other platforms.
- 🔊 **Premium Audio Quality** — Supports standard **192kbps** (Free) and up to **320kbps HIFI** (Premium) for the crystal-clear listening experience.
- 🎛️ **Rich Audio Filters** — Customize your music with filters: *Bassboost, 8D, Nightcore, Vaporwave, Karaoke, and more.*
- 🎮 **Intuitive Control Panel (Setup Panel)** — Create a dedicated music channel with a button-based UI. Play, pause, skip, or change volume without typing commands.
- 🤖 **Multi-Bot System** — Use the bot trio **BeeGold** (Primary), **BeeBlue**, and **BeePink** to stream concurrently in multiple voice channels.
- 📡 **24/7 Connection** — Keep the bot connected in your channel even when the queue is empty, ready for the next song (`/247`).
- 🔁 **Autoplay Mode** — Automatically search and play similar songs when the queue ends.
- 📝 **Personal Playlists** — Save your favorite tracks and play them back instantly anytime.
- 🇻🇳🇺🇸 **Dual Language Support** — Friendly English and Vietnamese interfaces, easy to configure.

---

## 🎮 Complete Command List (42 Commands)

BeeMusic uses Discord's intuitive Slash (`/`) command system. Below is the full command list categorized by features:

<details>
<summary>🎵 <b>1. Playback Commands (23 commands)</b></summary>

| Command | Description |
|---------|-------------|
| `/play <name / link>` | Search and play music from YouTube, Spotify, SoundCloud, Apple Music... |
| `/pause` | Pause the currently playing song |
| `/resume` | Resume playback of the paused song |
| `/skip` | Skip the current song and play the next one |
| `/stop` | Stop playback, clear the queue, and leave the voice channel |
| `/queue` | View the list of tracks in the queue |
| `/nowplaying` | Display details and progress of the currently playing track |
| `/volume <0-150>` | Adjust the bot's volume (Bronze max 120%, Silver+ max 150%) |
| `/join` | Make the bot join your voice channel |
| `/leave` | Disconnect the bot from the voice channel |
| `/loop <off/track/queue>` | Toggle loop mode for the current track or the entire queue |
| `/shuffle` | Shuffle the order of songs in the queue |
| `/seek <time>` | Seek to a specific timestamp (e.g., `1m30s`, `45s`) |
| `/forward <seconds>` | Fast forward the song by a specific duration |
| `/rewind <seconds>` | Rewind the song by a specific duration |
| `/lyrics [title]` | Search lyrics for the current song or any specified title |
| `/jump <index>` | Jump directly to a specific song number in the queue |
| `/previous` | Play the previously played track |
| `/replay` | Replay the current track from the beginning |
| `/grab` | Send details of the current song to your Direct Messages (DMs) |
| `/clearqueue` | Clear all tracks in the queue |
| `/remove <index>` | Remove a specific song from the queue by its index |
| `/removedups` | Scan and remove duplicate tracks from the queue |

</details>

<details>
<summary>🎛️ <b>2. Audio Filters (10 commands)</b></summary>

| Command | Description |
|---------|-------------|
| `/8d` | Apply the 8D rotating surround sound effect |
| `/bassboost <low/medium/high>` | Boost bass levels with adjustable intensity |
| `/clearfilter` | Remove all active audio filters |
| `/karaoke` | Filter out vocals to play only instrumental backing |
| `/lofi` | Apply a relaxing, low-fidelity chill filter |
| `/lowpass` | Apply a lowpass frequency cutoff filter |
| `/nightcore` | Speed up playback speed (tempo) and raise pitch |
| `/slowmode` | Slow down playback speed and tempo |
| `/timescale` | Manually scale playback speed and pitch |
| `/vaporwave` | Apply a slowed-down, aesthetic vaporwave audio filter |

</details>

<details>
<summary>📝 <b>3. Playlist Commands (1 command)</b></summary>

| Command | Description |
|---------|-------------|
| `/playlist` | Manage custom personal playlists (Create, delete, add, play) |

</details>

<details>
<summary>⚙️ <b>4. Settings Commands (4 commands)</b></summary>

| Command | Description |
|---------|-------------|
| `/247` | Toggle 24/7 mode to keep the bot connected in voice (requires Silver tier or higher) |
| `/setup` | Set up a static song requests channel with interactive button controller (Admin) |
| `/premium` | View package info and activate/deactivate Premium for the server |
| `/language` | Configure the bot's display and response language (English / Vietnamese) |

</details>

<details>
<summary>🛠️ <b>5. Utility Commands (4 commands)</b></summary>

| Command | Description |
|---------|-------------|
| `/ping` | Check connection latency to Discord and the music server |
| `/help` | Display the user guidebook and quick help menu |
| `/invite` | Get invitation links to add BeeMusic bots to your servers |
| `/sleeptimer <minutes>` | Set a timer to automatically stop music and leave after X minutes |

</details>

---

## 💎 What's Special About Premium?

Upgrade to **BeeMusic Premium** to unlock the full power of the bot:
- ⚡ **320kbps HIFI Audio Quality** — studio-grade sound.
- 🎛️ Unlock all **premium audio filters** (Extreme Bassboost, 8D effects...).
- 🔁 Save unlimited songs in your personal playlists.
- 👑 **Server-wide Premium Activation** (everyone in the server gets premium benefits).
- 🎨 Customize the bot's name and avatar to match your server style.
- 🚀 Priority connection bandwidth for lag-free playback.

👉 Upgrade now at: [beemusic.vncore.net](https://beemusic.vncore.net/)

---

## 📞 Technical Support

If you face any issues or want to leave feedback:
- **Support Discord Server:** [Join here (discord)](https://discord.gg/WfQmNFSAcq)
- **Website:** [beemusic.vncore.net](https://beemusic.vncore.net)
- **Contact Email:** support@vncore.net

---

<div align="center">
  Developed with 💛 by <a href="https://vncore.net">VNCore</a>
</div>
