# Traefik Ingress

This document provides a high-level overview of Traefik ingress in the Azure k3s lab.

## Purpose

Traefik is used as the ingress controller for exposing selected Kubernetes services in the lab.

## Main Use Cases

Traefik is used for:
- routing traffic to services
- testing ingress rules
- working with HTTP and HTTPS entry points
- learning service exposure patterns in Kubernetes

## Learning Goals

Using Traefik in the lab helps build practical understanding of:
- ingress controllers
- service routing
- public and internal access design
- troubleshooting ingress-related issues

## Notes

This repository documents the architecture at a high level. Sensitive hostnames, secrets and internal details are excluded.
