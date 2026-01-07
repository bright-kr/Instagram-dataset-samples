# instagram-dataset-samples

<h2>2180명의 Instagram 코딩 인플루언서 샘플 データセット</h2>

![instagram dataset header](https://github.com/luminati-io/Instagram-dataset-samples/blob/main/instagram-datasets.PNG)

2000명 이상의 주요 Instagram [Github](https://www.instagram.com/explore/tags/github/) 코딩 인플루언서에 대한 GitHub データセット 샘플입니다. データセット은 <b>Bright Data Collector</b>를 사용하여 추출되었습니다.

<h2>이 무료 データセット에 포함된 데이터 포인트:</h2>

* 팔로워 수
* 프로필 유형
* 계정 유형
* 참여 점수
* 카테고리
* 위치
* 외부/바이오 링크
* 사용된 해시태그
* 브랜드 제휴
* 바이오
* 하이라이트
* 게시물



이는 "All Instagram account, business & nonbusiness (public data)"
データセット에서 파생된 샘플 서브셋이며, 해당 データセット에는 <b>614,000,000개의 Instagram 프로필</b>이 포함됩니다.

이 예시에서는 Bright Data 컨트롤 패널에서 제공되는 스마트 필터 쿼리를 사용하여 대규모 データセット을 더 작은 서브셋으로 필터링했습니다.
<h2>이 서브셋을 필터링하는 데 사용된 쿼리:</h2>


*   	$or: [{"post_hashtags":"github"},{"bio_hashtags":"github"}]
*   	followers: {"$gt":100}

추가 필터 쿼리 값에는 <b>Posts count, cuntry, verified account, multiple hashtag combinations and more.</b>가 포함됩니다.

사용 가능한 データセット 파일 형식: <b>JSON, NDJSON, JSON Lines, CSV, or Parquet.</b>.

データセット 전달 유형 옵션: <b>API download, Amazon S3, Google cloud, Microsoft Azure, SFTP</b>.

추출된 데이터 포인트에 추가로 사용할 수 있는 데이터 강화: <b>Avg. post engagement rate, brand affiliation and more.</b>

전체 <b>[Instagram dataset](https://brightdata.co.kr/products/datasets/instagram)</b>을 확인하십시오.

<h2>추가로 사용 가능한 Instagram データセット:</h2>

*   635,000,000 "Instagram profiles dataset" 
*   89,000,000 "Instagram posts dataset"
*   12,490,000 "Instagram reels dataset"
*   206,000 "Instagram comments dataset"

<h2>학술 연구자 및 NGOs를 위한 Webスクレイピング 도구 및 データセット 무료 이용</h2>

Bright Initiative는 다양한 환경 및 사회적 목적을 증진하는 주요 학술 단과대학 및 연구자, NGOs 및 NPOs에 Bright Data의 [Web Scraper APIs](https://brightdata.co.kr/products/web-scraper) 접근 권한을 제공합니다. 신청서는 [here](https://brightinitiative.com)에서 제출할 수 있습니다.

### Instagram을 직접 スクレイピング하고 싶으신가요? [Instagram Scraper](https://brightdata.co.kr/products/web-scraper/instagram)를 사용하십시오.