---
layout: post
title:  "Cavity 필터 튜닝 자동화"
author: "Baby Apple"
---

강화 학습을 이용한 업계 최초 필터 튜닝 자동화 기술

## Motivation
- 100% 수작업으로 진행되는 Cavity 필터 튜닝 기술
- Cavity 필터는 4G/5G 기지국에 탑재되는 필수 장비로 정해진 대역에서 무선 통신을 가능하게 함
- 모든 튜닝은 사람이 진행하고, 작업자의 컨디션에 따른 정확도, 튜닝 속도 저하 문제가 발생

## Things I did
- 깊은 강화 학습을 이용한 자동 튜닝 기술 개발
- On Policy 방식의 Proximal Policy Optimization, Off Policy 방식의 Deep Deterministic Policy Gradient 사용
- 필터 튜닝 전문가와의 중간 보상 설계를 통한 학습 성공


