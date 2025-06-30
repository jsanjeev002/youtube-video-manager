# 🎬 YouTube Video Manager 📂

A simple command-line Python application to **manage your favorite YouTube videos** — add, view, update, and delete video records stored in a JSON file.

---

## 🧰 Features

- ✅ List all saved YouTube videos
- ➕ Add a new video with a name and duration
- ✏️ Update details of an existing video
- ❌ Delete a video from the list
- 💾 Stores data in a local `youtube.txt` file using JSON format

---

## 🖥️ Requirements

- Python 3.x

---

# 📂 File Structure

-Youtube-video-manager
<br>|
<br>├── youtube_manager.py   # Main Python application
<br>└── youtube.txt          # Auto-created JSON storage file

---

# 📋 Usage Example

Youtube Manager | choose an option
1. List all YouTube videos
2. Add a YouTube video
3. Update a YouTube video details
4. Delete a YouTube video
5. Exit the app

---

# ➕ Adding a Video

Enter video name: Learn Python in 1 Hour
Enter video time: 1:00:00

---

# 📝 Updating a Video

Enter the video number to update: 1
Enter video name: Advanced Python Tutorial
Enter video time: 2:15:00

---

# ❌ Deleting a Video

Enter the number of video you want to delete: 1

---

# 💡 Notes

- The app creates youtube.txt on first run if it doesn’t already exist.
- Make sure youtube.txt is in the same directory as your Python file.
- Video data is stored in JSON format like:

[
  {"name": "Python Basics", "time": "1:30:00"},
  {"name": "Flask Tutorial", "time": "2:00:00"}
]
