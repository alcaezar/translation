# 英语书籍翻译计划
该计划的宗旨为: 将以传授知识为目的的英文图书(纸质版/网页版)翻译成简体中文, 并统一制作成网页, 方便浏览.

## 正在进行的翻译计划

- [But How Do It Know](https://github.com/minecraft-in-python/but-how-do-it-know)
- [日语教科书](https://github.com/minecraft-in-python/nihongo-textbook)

## 跟踪翻译进度
请在各 GitHub Pages 服务的根目录下放置 `status.json` 文件表明翻译进度:
```json
{
	"total": "总数或者'unknow'(不方便统计)",
	"finish": "已完成的翻译(数字)"
}
```
> `已完成的翻译` 的统计数字应为单个包含翻译内容的文件

每个翻译计划都应在本仓库根目录下的 `projects.json` 留下记录:
```json
[
	{
		"name": "翻译计划的名称",
		"url": "翻译计划的网页, 例如 `https://**.github.io`"
	}
]
```

## 渲染 Markdown 文件
请借鉴 [minecraft-in-python/but-how-do-it-know](https://github.com/minecraft-in-python/but-how-do-it-know) 的做法.

- - -

# Translation
Translation project of Minecraft-in-python.

You can translate json files under every directories(base on English or Simplified Chinese).

## How To Translate JSON
It's an example:
```json
{
	"namespace1": "string1",
	"namespace2": [
		"string1",
		"string2"
	],
	"namespace3": {
		"situation1": "string1",
		"situation2": "string2"
	}
}
```

# How To Contribute
First, open an issue. It's name **must** include following things:

1. Which project
2. Which language
3. How lang to finish it

Then, you can fork this repo. Translate something.

Finally, create a Pull Requests and make a comment on the issue let others know you have finished it.
