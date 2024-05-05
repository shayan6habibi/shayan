{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8708:8446:c888:55aa:50ae/128"
      ],
      "private_key": "OPxMhFunRek1nbJm9DUIfU1vDiN31k6p3MJ5/gETXUY=",
      "server": "188.114.99.1",
      "server_port": 988,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [4,58,162],
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8117:8ce2:1884:b195:8454/128"
      ],
      "private_key": "eJfW9b8Fa7G/DhVvOhBmeEAJsr0Kn2TiWBPVNTzq4kA=",
      "server": "188.114.99.1",
      "server_port": 988,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [44,169,30],
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
