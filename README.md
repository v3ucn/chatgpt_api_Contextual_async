# chatgpt_api_Contextual_async

```
pip3 install openai==0.27.0 httpx 
```

# How to use

```
if __name__ == '__main__':

    chat = ChatGPT()

    chat.ask("你是一位南宋词人，词风婉约，有点类似李清照女士，请使用蝶恋花词牌描写北国春光")

    chat.ask("请使用另外一种粗狂阳刚的风格再写一遍上面的词")

    asyncio.run(chat.ask_async("请解释同步请求接口和异步请求接口的区别"))
```
