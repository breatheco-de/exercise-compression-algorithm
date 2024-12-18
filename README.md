<!--hide-->
# Compression Algorithm
<!--endhide-->

<p align="center">
    <img height="300" src="https://raw.githubusercontent.com/breatheco-de/exercise-compression-algorithm-python/master/preview.png" />
</p>

Let's create a compression algorithm 🤯
It sounds hard, but it's something achievable for almost anyone.

## 📝 Instructions

Create an algorithm that given a string, replaces its words matching the **`symbols` dictionary keys** and replaces them with their respective values on the same dictionary.

```python
symbols = {
    "implementation": "🤯",
    "practicality": '🤩',
    "better": '😅',
    "Although": "🥺"
}
```

For example:

| `Although, this is a great implementation of time` | → should become → | `🥺, this is a great 🤯 of time` |
| -------- | ------ | -------- |

The current project has 3 main files:

| Name | Description |
| -------- | ------ |
| compress.py | Contains the algorithm to compress the content, it has a function "compress" that receives the raw text and returns the compressed version of it |
| decompress.py | It's very similar to `compress.py` but it contains the algorithm to convert back the content from its compressed version to the original content |
| app.py | This is an entry file, and there is no need to update it, it imports and uses the other two files |

## 🔢 Steps

1. Take time to understand the code, start by opening and reading the `app.py` and follow the algorithm with your brain, review the compress.py and decompress.py files to understand where your solution must be implemented.
2. Run the app.py by typing `python3 app.py` and understand what is the output and why.
3. Edit the compress.py to create the **compression** algorithm.
4. Test your compression algorithm by running the app.py again.
5. Edit the decompress.py to create the **decompression** algorithm.
6. Test your decompression algorithm by running the app.py again.

<onlyfor saas="false" withBanner="false">

## 🌱 How to start this project

This project comes with the necessary files to get started, and you have two options to begin:

a) Open this link with [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod) in your browser: https://s.4geeks.com/start?repo=breatheco-de/exercise-compression-algorithm-python

b) Clone this repository locally on your computer:

```sh
$ git clone https://github.com/breatheco-de/exercise-compression-algorithm-python.git
```

### Steps

1. Run the following command in the terminal:

```bash
python3 app.py
```

You should get a response similar to this:

```bash
✅No data lost.
document.txt has 824 size, compressed.txt has 768 size, compression of 7% in 0.0003972053527832031 seconds 
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

</onlyfor>

## 🎯 Metrics

1. Compression power: Ratio is defined as the ratio between the uncompressed size and the compressed size.
2. No Data lost: If we compress and decompress document.txt the result should be the original string of content.

## 🍩🍬🍭 Feeling confident?

By adding more words to the `symbols` dict you can achieve more compression power.  

Try to re-do the algorithm to achieve a compression power above 15% with no data lost without just adding more words.
