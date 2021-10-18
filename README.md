```js
const followMe = [
    { name: 'Instagram', value: 'https://www.instagram.com/andregosling_/' },
    { name: 'GitHub', value: 'https://github.com/AndreGosling' },
]

for (const i in followMe) {
    const v = followMe[i]
    const platform = v.name
    platform.followUser({
        url: v.value
    })
}
```
