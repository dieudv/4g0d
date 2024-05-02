# 4G 0đ với Termux và SocksDroid trên Android

## Yêu cầu

**Sử dụng Android và cài 2 ứng dụng sau:**

- [Termux](https://play.google.com/store/apps/details?id=com.termux)
- [SocksDroid](https://apkcombo.com/socksdroid/net.typeblog.socks/)

## Cài đặt

**Copy, dán mã sau vào Termux và nhấn enter:**

    pkg upgrade -y && pkg install wget -y && \
    wget https://github.com/dieudv/4g0d/releases/download/v1/v1.zip && \
    unzip v1.zip -d 4g0d && cd 4g0d && \
    chmod a+x 4g && chmod a+x psiphon-tunnel-core && \
    echo 'PATH="$PATH:$HOME/4g0d"' >> $HOME/.bashrc && source $HOME/.bashrc && \
    echo 'PATH="$PATH:$HOME/4g0d"' >> $HOME/.zshrc && source $HOME/.zshrc && clear && cd

Trong quá trình chạy, nếu nó có hỏi gì thì nhấn enter hết nhé.
    
## Cấu hình & cách dùng

### Cấu hình SocksDroid:

DNS Server điền: `203.113.131.6`

Bật các mục: `Connect on Boot`, `Pre-app proxy`, `Bypass Mode`.

App List điền: `com.termux`

Xong thì gạt nút ở trên thanh tiêu đề để bật SocksDroid.
    
### Cách dùng:

Mở Termux và gõ `4g` và nhấn enter để bắt đầu sử dụng
