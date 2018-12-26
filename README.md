online_mode: true
log_commands: false
network_compression_threshold: 256
listeners:
- query_port: 25577
  motd: '&1mcgames server minetopia factions en nog meer #comming soon'
  tab_list: GLOBAL_PING
  query_enabled: true
  proxy_protocol: false
  forced_hosts:
    pvp.md-5.net: pvp
  ping_passthrough: false
  priorities:
  - lobby
  bind_local_address: true
  host: 0.0.0.0:25577
  max_players: 100
  tab_size: 60
  force_default_server: true
connection_throttle: 4000
