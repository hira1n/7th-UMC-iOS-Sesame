---
name: "\U0001F680 Bug"
about: Bug 발생 시 작성
title: ''
labels: ''
assignees: ''

---

labels: ["bug"]
body:
  - type: textarea
    attributes:
      label: 📌 상황 설명
      description: 어떤 상황에서 발생한 버그인가요?
      placeholder: "어떤 버그인지 간결하게 설명해주세요!"
    validations:
      required: true
  - type: textarea
    attributes:
      label: 🎯 예상 결과
      description: 예상했던 정상적인 결과가 어떤 것이었는지 설명해주세요
      placeholder: "정상적인 결과를 설명해주세요!"
    validations:
      required: true
  - type: textarea
    attributes:
      label: 📁 참고 자료
      description: 참고 자료가 있다면 작성해 주세요.
      placeholder: "관련 링크, 이미지, 로그 등을 추가해주세요."
  - type: textarea
    attributes:
      label: 📍 추가 정보
      description: 추가적인 로그, 스크린샷, 또는 관련 정보가 있다면 첨부해주세요.
      placeholder: "추가 정보가 있다면 작성해주세요."
