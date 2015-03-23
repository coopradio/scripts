#!/usr/bin/liquidsoap

# This lives on the logger at /usr/sbin/logging
 
set("log.file.path","/archive/log/archive-log.log")
input = input.alsa()
5 output.file(
    %mp3(stereo=true),
    "/archive/%m-%d-%H_%M_%S.mp3",
    reopen_when={0m0s},
    input
)
