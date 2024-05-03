{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8d37:40c5:28a1:8211:88b6/128"
      ],
      "private_key": "qFtOGz250sUpTR6XpGThjRN2RLN99gRrtPwZwPBps3g=",
      "server": "162.159.192.185",
      "server_port": 939,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [95,215,144],
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8031:a876:3d04:b1c9:c1b9/128"
      ],
      "private_key": "oJZi2mGZS9YZw4c6HsiLpDOJf6lMA8RiVlMReZS+tmg=",
      "server": "162.159.192.73",
      "server_port": 939,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [233,122,211],
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
