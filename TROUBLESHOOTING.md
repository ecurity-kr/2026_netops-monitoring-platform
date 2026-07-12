##  트러블슈팅 로그 (진행하며 계속 업데이트)

프로젝트 진행 중 겪은 issue와 해결 과정 기록

```
## [26-07-13] GNS3 Setup Wizard에서 "Could not find a VM named 'GNS3 VM'" 에러

**증상**: GNS3 Setup Wizard 진행 중 VirtualBox/VMware에서 GNS3 VM은 찾지 못함

**원인**: GNS3 VM.ova 파일을 VirtualBox에 아직 임포트하지 않은 상태에서
          Setup Wizard를 실행함.
          Virutalization software 선택이 VMware로 되어 있어 환경 불일치 확인함

**해결**: VirtualBox에서 File > Import Appliance로 GNS3 VM.ova 수동 임포트 후,
          Setup Wizard에서 Virtualization software를 VirtualBox로 명시적 선택
          위 설정 후 재시도

---

## [YY-MM-DD] 제목

**증상**: ...
**원인**: ...
**해결**: ...
