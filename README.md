# Wardialing Lab

## Description

This project scans IP address ranges in the DPRK to identify which ones host web servers.

## Running the Code

To run the wardialing script and find the IP addresses with servers:

```
python wardial.py
```

This will output the list of IP addresses that have web servers.

## Running the Tests

To run the doctests:

```
python -m doctest wardial.py
```

## Test Badge

<img src="https://github.com/ryankim8/lab-wardialing/workflows/doctests/badge.svg" />

## DPRK IPs with Servers

```
$ python wardial.py
dprk_ips_with_servers= ['175.45.176.68', '175.45.176.69', '175.45.176.71', '175.45.176.75', '175.45.176.76', '175.45.176.80', '175.45.176.91', '175.45.177.1', '175.45.177.10', '175.45.177.11']
```
