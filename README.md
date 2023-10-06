# Extract Contact Patch Signal using P33V and Frequency Domain
- 무선 전력 전압(P33V_MON)을 기준으로 타이어 내부 센서가 위치하는 각도를 계산하고, 센서가 지면에 닿을 것으로 예상되는 각도 범위 선정
- 해당 각도 범위 내에서 주파수 영역 분석을 통해 Contact Patch 신호를 추출
- (Contact Patch Extraction.pptx 참고)

# Road Classification CNN Model
- 3축 가속도 신호를 RGB 채널 Spectrogram 이미지로 변환
- RGB Spectrogram 이미지를 입력으로 시험로를 분류하는 CNN 모델 학습
- 모델의 학습 과정 시각화
- (Signal Classification.pptx 참고)