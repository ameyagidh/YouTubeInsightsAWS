# EndlessTube AWS

kaggle dataset Link:- https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download

Uploading Data To S3 bucket

cd to the data directory and then type this command

aws s3 cp . s3://youtube-analyticsbucket-ameya/youtube/raw_statistics_reference_data/ --recursive --exclude "" --include ".json"
