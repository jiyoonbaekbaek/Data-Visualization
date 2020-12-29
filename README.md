# Data-Visualization (basic)

These are tutorial codes I've used for data visualization. All the codes are provided from the following lectures and books. I just modified those a bit to visualize the data I found interesting 

# tutorials :
- https://www.youtube.com/watch?v=Pkvdc2Z6eBg'. (seaborn)
- <파이썬 머신러닝 판다스 데이터 분석> (pandas)
- <Matplotlib Tutorial - 파이썬으로 데이터 시각화하기> (matplotlib)

# seaborn  : 
- lineplot
- barplot
- histogram 
- boxplot
- scatterplot
- lmplot 
- subplot
- pairplot
- joinplot
- heatmap
- data : K-pop Girl Groups (1992-2020)
	- source :  dbkpop (K-pop Database)
	
	 flights.csv (BI report) 
	
# pandas : 
 ## part 1:
 - set_index 메소드
 - reindex 메소드
 - reset_index 메소드
 - sort_values 메소드
 - 시리즈 vs 숫자
 - 시리즈 vs 시리즈
 - 데이터프레임 vs 숫자
 - 데이터프레임 vs 데이터프레임
 
 ## part 2:
 - csv 파일 읽기
 - 엑셀 파일 읽기
 - json 파일로 저장
 - 엑셀 파일로 저장
 - 여러 개의 데이터프레임을 하나의 엑셀 파일로 저장
 
 ## part 3:
 - df.shape
 - df.info
 - df.dtypes
 - df.describe(include='all')
 - df.count()
 - df['열 이름'].value_counts()
 - df[상관관계를 구하고 싶은 열 목록 리스트].corr()
 
 ## part 4 :
 skipped most of the visualization parts since I'm already learning sns,plt separately from different sources
 - Folium 라이브러리 - 지도 활용 시각화 
 
 
# Matplotlib : 
 ## 1 ~ 3 :
 - plt.plot()
 - plt.axis()
 - plt.xlabel(...,fontdict,labelpad,...)
 - plt.ylabel(...,fontdict,labelpad,...)
 
 ## 4 ~ 8 :
 - 4. plot 메소드의 라벨을 지정하고 legend 호출
 범례 위치 지정하기 : legend 메소드의 loc 옵션
 범례에 표시될 열 갯수 조정하기 : legend 메소드의 ncol 옵션
 범례에 표시될 폰트 크기 조정하기 : legend 메소드의 fontsize 옵션
 범례 테두리 꾸미기 : legend 메소드의 frameon,shadow 등등의 옵션
 - 5. 축 범위 지정하기
 xlim([xmin,xmax])
 ylim([ymin,ymax])
 axis([xmin,xmax,ymin,ymax]) : 입력값이 없으면 데이터에 맞게 자동으로 범위 지정
 - 6. 마커 지정하기
 plot 함수 내 지정 eg. 'bo' , 'bo--' ,...
 - 7. 색상 지정하기
 - 8. Matplotlib 그래프 영역 채우기 : 그래프의 특정 영역을 색상으로 채워서 강조
 how ?
 fill_between() : 두 수평 방향의 곡선 사이를 채우기 (두 그래프 사이 영역 채우기)
 fill_betweenx() : 두 수직 방향의 곡선 사이를 채우기
 fill() : 다각형 영역을 채우기


