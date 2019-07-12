A fork of [st](https://st.suckless.org/) with the following patches applied.

1. anysize ([st-anysize-0.8.1.diff](https://st.suckless.org/patches/anysize/st-anysize-0.8.1.diff)):

    Allows st to resize to any pixel size, makes the inner border size dynamic, and centers the content of the terminal so that the left/right and top/bottom borders are balanced.

2. xresources ([st-xresources-20190105-3be4cf1.diff](https://st.suckless.org/patches/xresources/st-xresources-20190105-3be4cf1.diff)):

    Adds the ability to configure st via Xresources. At startup, st will read and apply the resources named in the resources[] array in config.h.
