# EndlessTube AWS

kaggle dataset Link:- https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download

Uploading Data To S3 bucket

cd to the data directory and then type this command

aws s3 cp . s3://youtube-insights-bucket-ameyasgidh/youtube/raw_statistics_reference_data/ --recursive --exclude "*" --include "*.json"

### Seperate the data into respective folder based on their regions
aws s3 cp CAvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=ca/

aws s3 cp DEvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=de/

aws s3 cp FRvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=fr/

aws s3 cp GBvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=gb/

aws s3 cp INvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=in/

aws s3 cp JPvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=jp/

aws s3 cp KRvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=kr/

aws s3 cp MXvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=mx/

aws s3 cp RUvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=ru/

aws s3 cp USvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=us/

aws s3 cp MXvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=mx/

aws s3 cp RUvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=ru/

aws s3 cp USvideos.csv s3://youtubeinsightsbucket-ameya/youtube/raw_statistics/region=us/
