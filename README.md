# 👤 I'm **vxnetrip** — welcome to my GitHub.
```asm
section .data
    message_format db "Follow %s on Github", 10, 0
    username db "vxnetrip", 0

section .text
    global main
    extern printf
    extern exit

main:
    sub rsp, 40
    mov rcx, message_format
    lea rdx, [rel username]
    call printf
    mov ecx, 0
    call exit
```

### 😵‍💫 About me in a nutshell
```bash
[vx@archlinux ~]$ gcc time.c
cc1: fatal error: time.c: No such file or directory
compilation terminated.
```

### 💀 I am a programmer contact etc ble ble ble:

> 📂・**Latest soon coming project**: NULL

> 🌐・**Check Out My Website**: [https://vxnet.onrender.com](https://vxnet.onrender.com)

> 📩・**Want to reach? Add @vxnetrip on [discord](https://discord.com/users/1126449850041511986) or join my [discord server](https://discord.gg/Y6XMxTW5u5)**

### 💳 Stats: 

<div align="center">
    <h2 align="center">⚡ Statistics</h2>
    <div>
        <img src="https://github-readme-stats.vercel.app/api?username=vxnetrip&show_icons=true&bg_color=00000000">
    </div>
    <div>
        <img src="http://github-readme-streak-stats.herokuapp.com?user=vxnetrip&theme=tokyonight_duo&hide_border=true&mode=weekly">
    </div>
</div>
