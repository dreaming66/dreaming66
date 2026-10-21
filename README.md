<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=520&lines=Hi%2C+I'm+Ruimin+%F0%9F%91%8B;Scheduling+GPUs+so+you+don't+have+to;kubectl+get+pods+--watch+%F0%9F%91%80;It's+not+a+bug%2C+it's+a+race+condition;Currently+in+Beijing+%F0%9F%A5%9F" alt="Typing SVG" />

<img src="https://komarev.com/ghpvc/?username=dreaming66&color=blueviolet&style=flat-square&label=humans+who+wandered+in" alt="Profile views" />

</div>

```console
$ kubectl describe human ruimin
Name:         ruimin
Namespace:    beijing
Labels:       role=ai-infra
              mood=compiling
Containers:
  brain:
    Image:    go:latest + python:3
    Limits:   coffee=unlimited
Conditions:
  Type        Status
  Curious     True
  Sleepy      Unknown
Events:
  Normal  Scheduled  just now  Waiting for the next interesting bug
```

## 🐍 My contributions, being eaten

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dreaming66/dreaming66/output/github-snake-dark.svg" />
  <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/dreaming66/dreaming66/output/github-snake.svg" />
</picture>

## 🥧 Where my time actually goes

```mermaid
pie showData
    "Waiting for CI" : 35
    "Reading YAML" : 25
    "Writing code" : 15
    "Googling the error" : 15
    "kubectl delete pod (and hoping)" : 10
```

## 🧭 My debugging algorithm

```mermaid
flowchart TD
    A[🔥 Something is broken] --> B{Did it work yesterday?}
    B -- Yes --> C[git log --since=yesterday]
    B -- No --> D{Is it DNS?}
    D -- Yes --> E[It's always DNS 🙃]
    D -- "No (it's DNS)" --> E
    C --> F[Blame past me]
    E --> G[Restart the pod]
    F --> G
    G --> H{Fixed?}
    H -- Yes --> I[🎉 Ship it]
    H -- No --> J[☕ More coffee]
    J --> A
```

## 🤹 Today's joke (refresh for another)

<div align="center">

<img src="https://readme-jokes.vercel.app/api?theme=tokyonight" alt="Random dev joke" />

</div>

## 🔁 Daily loop

```python
while alive:
    coffee += 1
    if cluster.is_on_fire():
        kubectl("describe", "pod", cluster.loudest_pod())
    elif ci.is_green():
        celebrate()          # rare event, handle with care
    else:
        wait_for_ci()        # 90% of runtime
    sleep(random.choice([0, 0, 0, 8]))  # sleep is a best-effort operation
```

## 💬 Words to live by

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random dev quote" />

</div>

<details>
<summary>🚫 <b>Do not click</b></summary>

<br />

```console
$ kubectl delete namespace production
namespace "production" deleted

$ echo "just kidding"
just kidding
```

You clicked anyway. A true infra engineer. 🫡 You are now on call.

</details>

<div align="center">

**Go · Python · Kubernetes · Docker · Shell · TypeScript / React**

*"It works on my cluster."* 🚢

```text
      /\_/\      sudo make me a sandwich
     ( o.o )     > okay.
      > ^ <
```

</div>
