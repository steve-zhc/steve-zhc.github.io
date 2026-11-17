# violin&flute workshop

**[打开网站 · Open the workshop](https://steve-zhc.github.io/)**

## 软件介绍 · About

**中文**  
violin&flute workshop 是面向小提琴与长笛学习的互动音乐教具，将乐器指法、五线谱、音色试听与分级训练融于一体。课堂上，教师可通过投屏演示指法与音符的对应关系，组织识谱、听辨和节奏接龙互动；课后，学生可自主练习音阶琶音、巩固听辨与节奏能力，通过错题复练、练习记录和神兽成长保持学习动力，让课堂所学延续到日常练习。

**English**  
violin&flute workshop is an interactive learning tool for violin and flute, bringing together fingering, staff notation, sound demonstrations and graded exercises. In class, teachers can project the instrument models to demonstrate how fingerings relate to notes and lead notation, listening and rhythm activities. At home, students can practise scales and arpeggios, strengthen listening and rhythm skills, revisit mistakes and follow their progress, with evolving musical companions adding encouragement along the way.

## 功能概述 · Key features

- **乐器与指法 / Instruments & fingering** — 小提琴与长笛交互模型、指法提示、音名与唱名对应、五线谱显示、音色试听，以及麦克风辅助音高检测。Interactive instrument models, fingering cues, note names and solfège, staff notation, sound playback and microphone-assisted pitch detection.
- **分级基础训练 / Graded musicianship** — 五级递进的识谱、听音、音程、和弦与旋律复现练习。Five levels of notation, pitch, interval and chord recognition, plus melody recall by selecting solfège in sequence.
- **音阶与节奏 / Scales & rhythm** — 大小调音阶、琶音与半音阶谱例，支持变速示范和节拍器；节奏训练与接龙提供预备拍、模仿练习及准确率反馈。Major and minor scales, arpeggios and chromatic exercises with adjustable playback and a metronome; rhythm practice and call-and-response activities with count-ins and accuracy feedback.
- **记录与复习 / Progress & review** — 练习时长曲线、模块准确率、分类错题复练，以及基于作答记录的学习建议。Practice-time charts, accuracy by module, targeted mistake review and suggestions based on recorded answers.
- **陪伴与适配 / Companions & access** — 六套神兽、五级进化与音乐知识气泡；支持电脑和 iPad 布局、深浅主题及 JSON 进度备份。Six musical companions with five growth stages and musical facts, desktop and iPad layouts, light and dark themes, and JSON progress backups.

## 使用说明 · Usage

- 正式网址需要联网访问；保存完整 HTML 可作为本地离线副本使用。The website requires a connection to load; a saved standalone HTML copy can run locally offline.
- 姓名与学习进度保存在当前设备的当前浏览器中，不会自动跨设备同步。可用“进度备份”导出、导入 JSON；从本地版迁移到网站时也需手动导入。Names and progress are stored in the current browser. Use JSON export/import to back up or transfer progress, including when moving from a local copy to the website.
- 麦克风需浏览器授权；音高检测用于辅助练习。旋律复现核对点选音序，不检测歌声音准；音阶练习不提供整曲演奏自动评分。Microphone access requires permission. Pitch detection supports practice; melody recall checks selected note sequences rather than sung pitch, and scale exercises do not automatically grade a complete performance.
- 学习建议由本地练习统计生成，不依赖在线 AI 服务。Learning suggestions are generated from local practice statistics without an online AI service.
- 推荐使用较新的 Chrome、Edge 或 Safari。声音在用户点击后启动。A recent Chrome, Edge or Safari browser is recommended; sound starts after a user interaction.

## 发布与维护 · Publishing & maintenance

`index.html` 是完整、可编辑的单文件发布源码；核心音色、字体与谱面组件均内嵌，`.nojekyll` 用于直接托管静态文件。个人进度 JSON 和本地创作归档不随网站公开上传。`index.html` is the editable, standalone release source with embedded core sounds, fonts and notation components. Personal progress backups and local creation archives are not published in this repository.

版本 / Release：2026-11-17。页面源码 / HTML SHA-256：

`2fbd48ace5fa5ab52adf6090a5a20e44c35ca0efaaca1827524fa3925d4c3837`

第三方组件、字体和音色的许可声明保留在 HTML 中；公开访问不代表可移除这些声明或另行分发受保护内容。Third-party component, font and sound licences remain in the HTML; public access does not grant permission to remove these notices or redistribute protected content.
