http:
  routers:
    gitea:
      rule: "Host(`git.office.yimeng.ch`)"
      service: gitea
      tls:
        certresolver: myresolver

  services:
    gitea:
      loadBalancer:
        servers:
          - url: "http://127.0.0.1:3000/"
      