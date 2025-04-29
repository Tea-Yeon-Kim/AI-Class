# AI-Class
인공지능개론 수업 과제 제출
for col in data.columns:
    if isinstance(data[col].dropna().iloc[0], pd._libs.interval.Interval):
        print(f"Interval 타입 컬럼 발견: {col}")
