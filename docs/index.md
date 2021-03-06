# Prometheus2-grafana-dashboard
This dashboard was created as substitution for dashboard
[Prometheus Benchmark](https://grafana.com/dashboards/1244) after the
version `2.0.0` release. The original dashboard was not yet modified
to reflect breaking changes in metrics exposed by Prometheus itself so
i made my own.

Hopefully people from Robust Perception will get to the update of their
official dashboard but meanwhile mo own will do the trick for me.

Feel free to use, comment, fork and make pull requests whatever you like.

## Installation
There are three ways to install this dashboard

   1. Copy the [`JSON` definition](https://raw.githubusercontent.com/FUSAKLA/Prometheus2-grafana-dashboard/master/dashboard/prometheus2-dashboard.json)
   of dashboard and paste it in the Import dialog in Grafana
   2. Download the [`JSON` definition](https://raw.githubusercontent.com/FUSAKLA/Prometheus2-grafana-dashboard/master/dashboard/prometheus2-dashboard.json)
   and using the `Upload .json file` dialog
   3. Load the dashboard directly form Grafana.com website using
   dashboard ID `3681` or on link https://grafana.com/dashboards/3681


## Description

*I will add some basic description for every row i hope*


## Screenshots
![screenshot1](https://grafana.com/api/dashboards/3681/images/2334/image "Top of dashboard with main info")

![screenshot2](https://grafana.com/api/dashboards/3681/images/2340/image "Data storage info")

![screenshot3](https://grafana.com/api/dashboards/3681/images/2337/image "Resources consumption (usin heapster)")

## Support

Sadly I don't use exact version in production due to some architectonic
reasons and optimizations for my own setup but it's very much the same.

But i will try to sometimes update this dashboard if I make some major changes.


## Credits

I would like to thank all people from Robust Perception
working on Prometheus and also Grafana developers. You are doing
amazing job :)

This dashboard is partially build on the above mentioned
[Prometheus Benchmark](https://grafana.com/dashboards/1244)
dashboard so the credits goes to the Robust Perception.