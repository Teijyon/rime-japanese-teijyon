# rime-japanese-teijyon

## About

This is a layout for typing in Ryukyuan 琉球语 (mainly Okinawan/Uchinaaguchi 沖縄語／うちなーぐち／冲绳语). Supports words in all 3 scripts (Kanji, Hiragana, Katakana).


## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `teijyon/rime-japanese-teijyon` using plum:

```bash
bash rime-install teijyon/rime-japanese-teijyon
```

Finally edit `default.custom.yaml` and add `japanese` to the schema list:

```bash
patch:
  schema_list:
    - schema: japanese
```

Now reload RIME and it should appear under your layouts.

# Feedback

This is still a project under construction in spare time. Any feedback or typo/bug catch is welcomed and can be submitted to liuqiuyu.abc@gmail.com. 