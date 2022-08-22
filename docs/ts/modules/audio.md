# Module audio.ts(audio.js)

```typescript
import {} from "bilibili-api-ts/audio"
```

音频相关

## class Audio

音频类。

### Functions

#### constructor

| name       | type                 | description            |
| ---------- | -------------------- | ---------------------- |
| auid       | int                  | 音频 AU 号             |
| credential | Credential, optional | 凭据. Defaults to None |

#### function get_auid()

获取 auid

**Returns:** auid

#### async function get_info()

获取音频信息

**Returns:** API 调用返回结果

#### async function get_tags()

获取音频 tags

**Returns:** API 调用返回结果

#### async function get_download_url()

获取音频下载链接

**Returns:** API 调用返回结果

## class AudioList

歌单

### Functions

#### constructor()

| name       | type                 | description            |
| ---------- | -------------------- | ---------------------- |
| amid       | int                  | 歌单 ID                |
| credential | Credential, optional | 凭据. Defaults to None |

#### async function get_info()

获取歌单信息

**Returns:** API 调用返回结果


#### async function get_tags()

获取歌单 tags

**Returns:** API 调用返回结果

#### async function get_song_list()

| name | type          | description         |
| ---- | ------------- | ------------------- |
| pn   | int, optional | 页码。Defaults to 1 |

获取歌单歌曲列表

**Returns:** API 调用返回结果
