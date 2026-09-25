<p align="center">
  <img src="assets/logo.png" alt="minidock logo: a blue hermit crab peeking out of a cardboard box labelled 1 PROCESS" width="200">
</p>

<p align="center">
  <img src="assets/cover.jpg" alt="minidock: a shipping label on a cardboard box — Docker, packed small, built by hand from raw Linux syscalls" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/language-C11-2447D6?style=flat-square" alt="language: C11">
  <img src="https://img.shields.io/badge/platform-Linux%20%E2%89%A5%205.19-121417?style=flat-square" alt="platform: Linux 5.19 or newer">
  <img src="https://img.shields.io/badge/cgroups-v2-2447D6?style=flat-square" alt="cgroups: v2">
  <img src="https://img.shields.io/badge/status-learning%20project-bf8700?style=flat-square" alt="status: learning project">
  <img src="https://img.shields.io/badge/license-MIT-1a7f37?style=flat-square" alt="license: MIT">
</p>

<p align="center">
  <b>A tiny container runtime, written by hand in C, to understand what Docker actually does.</b><br>
  No libraries. No daemon. Just <code>clone()</code>, <code>mount()</code>, <code>pivot_root()</code>, <code>setns()</code> and files under <code>/sys/fs/cgroup</code>.
</p>
