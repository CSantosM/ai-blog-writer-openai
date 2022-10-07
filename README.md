# AI Blog Writer with OpenAI GPT-3
Create an AI blog writing tool with Open AI API.


```sh
docker build -f docker/dockerfile -t openai .

docker run -p 8888:8888 -e OPENAI_API_KEY=your-key openai

```