---
id: port-management
title: নোডগুলির জন্য প্রযুক্তিগত পরিকাঠামো
sidebar_label: Technical Infrastructure For Nodes
description: Polygon নোড-এ ব্যবহৃত ডিফল্ট পোর্টের তালিকা
keywords:
  - docs
  - polygon
  - matic
  - port
  - port management
  - infrastructure
  - default ports
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

এখানে Polygon-এর নোডগুলি জুড়ে ব্যবহৃত ডিফল্ট পোর্টগুলির একটি তালিকা দেওয়া হলো:

## Bor {#bor}

| ﻿নাম | পোর্ট | ট্যাগ | বিবরণ |
|------------------------|-------|---------------------------|----------------------------------------------------------------------------------------------------------------|
| নেটওয়ার্ক লিসেনিং পোর্ট | 30303 | পাবলিক | নেটওয়ার্ক লিসেনিং পোর্ট। সঙ্গীদের সংযুক্ত করতে এবং সিঙ্ক করতে Bor এই পোর্ট ব্যবহার করে |
| RPC সার্ভার | 8545 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | লেনদেন পাঠানোর জন্য এবং Bor থেকে ডেটা পাওয়ার জন্য RPC পোর্ট। Heimdall চেকপয়েন্টের জন্য Bor হেডার পেতে এই পোর্টগুলি ব্যবহার করে |
| WS সার্ভার | 8546 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Websocket পোর্ট |
| Graphql সার্ভার | 8547 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Graphql পোর্ট |
| Prometheus সার্ভার | 9091 | সর্বজনীন হতে পারে, পর্যবেক্ষণরত | Grafana-তে ডেটাসোর্স হিসাবে Prometheus সার্ভারের API। এটি nginx-এর রিভার্স প্রক্সির মাধ্যমে 80/443 এ ম্যাপ করা যেতে পারে |
| Grafana সার্ভার | 3001 | সর্বজনীন হতে পারে, পর্যবেক্ষণরত | Grafana ওয়েব সার্ভার। এটি nginx-এর রিভার্স প্রক্সির মাধ্যমে 80/443 এ ম্যাপ করা যেতে পারে |
| Pprof সার্ভার | 7071 | অভ্যন্তরীণ, পর্যবেক্ষণরত | Bor থেকে মেট্রিক্স সংগ্রহ করার জন্য Pprof সার্ভার |
| UDP ডিসকভারি | 30301 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Bootnode ডিফল্ট পোর্ট (পিয়ার ডিসকভারির জন্য) |

## Heimdall {#heimdall}

| ﻿নাম | পোর্ট | ট্যাগ | বিবরণ |
|------------------------|-------|---------------------------|----------------------------------------------------------------------------------------------------------------|
| নেটওয়ার্ক লিসেনিং পোর্ট | 30303 | পাবলিক | নেটওয়ার্ক লিসেনিং পোর্ট। সঙ্গীদের সংযুক্ত করতে এবং সিঙ্ক করতে Bor এই পোর্ট ব্যবহার করে |
| RPC সার্ভার | 8545 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | লেনদেন পাঠানোর জন্য এবং Bor থেকে ডেটা পাওয়ার জন্য RPC পোর্ট। Heimdall চেকপয়েন্টের জন্য Bor হেডার পেতে এই পোর্টগুলি ব্যবহার করে |
| WS সার্ভার | 8546 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Websocket পোর্ট |
| Graphql সার্ভার | 8547 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Graphql পোর্ট |
| Prometheus সার্ভার | 9091 | সর্বজনীন হতে পারে, পর্যবেক্ষণরত | Grafana-তে ডেটাসোর্স হিসাবে Prometheus সার্ভারের API। এটি nginx-এর রিভার্স প্রক্সির মাধ্যমে 80/443 এ ম্যাপ করা যেতে পারে |
| Grafana সার্ভার | 3001 | সর্বজনীন হতে পারে, পর্যবেক্ষণরত | Grafana ওয়েব সার্ভার। এটি nginx-এর রিভার্স প্রক্সির মাধ্যমে 80/443 এ ম্যাপ করা যেতে পারে |
| Pprof সার্ভার | 7071 | অভ্যন্তরীণ, পর্যবেক্ষণরত | Bor থেকে মেট্রিক্স সংগ্রহ করার জন্য Pprof সার্ভার |
| UDP ডিসকভারি | 30301 | সর্বজনীন হতে পারে, অভ্যন্তরীণ | Bootnode ডিফল্ট পোর্ট (পিয়ার ডিসকভারির জন্য) |