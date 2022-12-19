# Open Network-Internet Communication Protocol

Version 1

December 19th, 2022

## Table of Contents
1. [Introduction](#introduction)
2. [Overview](#overview)

## Introduction
The Open Network-Internet Communication (ONIC) protocol standardizes secure, reliable, and efficient communication between two (or more) machines over the Internet.

This specification assumes knowledge of the User Datagram Protocol (UDP) [1] and some topics of cryptography including: symmetric and asymmetric encryption, hashing, public/private keys, and digital signatures.

## Overview
This section focuses on the terminology and the communication models of the ONIC protocol. The terms used throughout this document are specific to the protocol and are not general terminology.

| Term    | Definition                                                                               |
|---------|------------------------------------------------------------------------------------------|
| client  | an application that implements the ONIC protocol                                         |
| contact | information about a remote client to facilitate connections with the remote client       |
| session | an active connection between two clients                                                 |
| channel | a client that acts as a (relay) server or middleman between clients                      |
| message | a packet sent from one client to another, following the ONIC protocol message structure  |
| page    | a text-only communication channel between two clients, to facilitate general messaging   |
| stream  | a continous data stream between two clients, to facilitate general data or file transfer |
