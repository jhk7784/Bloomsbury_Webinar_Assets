# Bloomsbury Webinar — Public Assets

Public image assets for the [Bloomsbury Webinar](https://github.com/jhk7784/Bloomsbury_Webinar) project.

This repo exists separately from the main (private) webinar repo so that image assets are accessible to external tools (Claude Design, claude.ai vision, etc.) via GitHub raw URLs.

## Structure

```
physics/    — 물리 섹션 PPTX 추출 이미지 (15장)
              파일명: physics_slide<NNN>_img<N>.<ext>
              출처: [물리] 설명회 자료 (V2).pptx
```

## URL 패턴

```
https://raw.githubusercontent.com/jhk7784/Bloomsbury_Webinar_Assets/main/<folder>/<filename>
```

예시:
```
https://raw.githubusercontent.com/jhk7784/Bloomsbury_Webinar_Assets/main/physics/physics_slide001_img1.png
```

## 동기화

메인 webinar 레포의 `public/slides_data_physics/images/` → 이 레포의 `physics/` 으로 복사.
