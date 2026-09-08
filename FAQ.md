# ChapterFlow for YouTube™ — Frequently Asked Questions (FAQ)

### General Questions

#### What is ChapterFlow for YouTube™?
ChapterFlow is a lightweight browser extension designed for podcast listeners and long-form video consumers. It extracts YouTube video chapters into an interactive panel, allowing you to select only the topics you want to hear and skip the rest automatically.

#### How does ChapterFlow skip chapters?
When playback reaches a chapter you have unchecked in the list, ChapterFlow instantly jumps to the start timestamp of the next checked chapter using native HTML5 video controls.

#### Is ChapterFlow an ad blocker or SponsorBlock alternative?
No. ChapterFlow is not an ad blocker and does not attempt to detect or mute ads/sponsors automatically via external databases. It relies strictly on the native video chapters provided by the content creator, giving you manual control over topic selection.

---

### Usage & Troubleshooting

#### Why aren't chapters loading for a video?
ChapterFlow relies on creators adding timestamps to their videos. If a video does not have native YouTube chapters in its description or player bar, ChapterFlow will not have any chapters to display.

#### Can I quickly filter topics in long podcasts?
Yes! Use the built-in search bar in the ChapterFlow panel to type keywords (e.g., "tech" or "Q&A"). The panel will immediately display only the matching chapters while preserving your existing checkmarks.

#### Does ChapterFlow remember my selections if I refresh the page?
Selections are configured per video session. Currently, resetting or navigating away clears the active session checklist so you can start fresh on the next video.

---

### Privacy & Permissions

#### Does ChapterFlow collect my browsing data?
No. ChapterFlow operates 100% locally in your browser. We do not track your watch history, collect personal data, or communicate with external servers.

#### What permissions does ChapterFlow require?
ChapterFlow only requests access to `storage` (to remember panel preferences locally) and script execution on `youtube.com/watch` pages to read chapter timestamps and control playback.

---

### Support & Feedback

#### I found a bug or have a feature request. How can I report it?
Please open an issue on our [GitHub Issue Tracker](https://github.com/chapterflow-app/chapterflow-extension/issues). We actively review community feedback!
