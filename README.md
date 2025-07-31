## Json 数据结构说明

```
// data文件夹里的bannerList.json
{
  "id": 1, // id值是唯一性，可以为空，代码暂时没用到
  "image": "https://picsum.photos/id/1/1200/400", // 超链接路径或者本地路径（/images/banner/xxxx.png）
  "alt": "" //图片说明，图片没有显示成功会提供文字说明，可以为空
}

// data文件夹里的didList.json
{
  "id": 1,  // id值是唯一性，可以为空，代码暂时没用到
  "title": "人工智能新突破123", //主标题
  "description": "探索人工智能领域的最新技术和应用案例，了解AI如何改变我们的生活和工作方式。", //副标题
  "image": "/images/didList/tupian1.png", // 超链接路径或者本地路径（/images/didList/xxxx.png）
  "alt": "", //图片说明，图片没有显示成功会提供文字说明，可以为空
  "link": "https://www.baidu.com", //跳转到新页面链接，可以为空，会弹出无外链提示
  "date": "2025-07-15" //日期
}


// data文件夹里的wroteList.json
{
  "id": 1,  // id值是唯一性，可以为空，代码暂时没用到
  "title": "人工智能新突破123", //主标题
  "description": "探索人工智能领域的最新技术和应用案例，了解AI如何改变我们的生活和工作方式。", //副标题
  "link": "https://www.baidu.com", //跳转到新页面链接，可以为空，会弹出无外链提示
  "date": "2025-07-15" //日期
}
```
