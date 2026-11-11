# 옵이음 HUD 리소스팩 배포

Paper 26.3 서버의 MyPet + AuraSkills 하단 HUD 리소스팩 공개 배포 저장소입니다.

## 파일 업로드 및 자동 배포

1. GitHub 저장소에서 **Add file → Upload files** 선택
2. `ObieumHUD-26.3-resourcepack.zip` 파일을 **저장소 최상위**에 추가
3. `Commit changes` 클릭
4. GitHub Actions의 `Publish Minecraft Resource Pack` 작업이 성공하면 Releases에 `v1.0.0` 자동 생성

배포 파일: `ObieumHUD-26.3-resourcepack.zip`

**SHA-1 (해당 빌드):**
`eec5d2561502f512928bef03fadd22dc734d5e3f`

직접 다운로드 주소 (배포 완료 후):
`https://github.com/Insiks/Obieum-ResourcePack/releases/download/v1.0.0/ObieumHUD-26.3-resourcepack.zip`

서버의 `server.properties` 설정:

```properties
resource-pack=https://github.com/Insiks/Obieum-ResourcePack/releases/download/v1.0.0/ObieumHUD-26.3-resourcepack.zip
resource-pack-sha1=eec5d2561502f512928bef03fadd22dc734d5e3f
require-resource-pack=false
```

새 ZIP으로 교체하면 SHA-1이 달라질 수 있으니 갱신해야 합니다.
