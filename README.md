[![.NET](https://github.com/zimbres/UptimeKumaRemoteProbe/actions/workflows/dotnet.yml/badge.svg)](https://github.com/zimbres/UptimeKumaRemoteProbe/actions/workflows/dotnet.yml) [![.CodeQL](https://github.com/zimbres/UptimeKumaRemoteProbe/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/zimbres/UptimeKumaRemoteProbe/actions/workflows/codeql-analysis.yml)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzimbres%2FUptimeKumaRemoteProbe.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzimbres%2FUptimeKumaRemoteProbe?ref=badge_shield)

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=zimbres_UptimeKumaRemoteProbe)](https://sonarcloud.io/summary/new_code?id=zimbres_UptimeKumaRemoteProbe)


# Uptime Kuma Remote Probe

>Uptime Kuma repository https://github.com/louislam/uptime-kuma

---

Services configuration is done by editing the file appsettings.json and restarting application.

`"UpDependency": "192.168.1.1"` should be a trustable IP in your network, your ISP gateway for example. In case of this IP is not available, no other checks will be executed.

`"Delay": 5000` is the delay time between checks. It is expressed in milliseconds, in this example 5 seconds between each round.

---

Pré compiled package is available for Windows and Linux. It requires .Net Runtime 6.x.

[Download .NET 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzimbres%2FUptimeKumaRemoteProbe.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzimbres%2FUptimeKumaRemoteProbe?ref=badge_large)