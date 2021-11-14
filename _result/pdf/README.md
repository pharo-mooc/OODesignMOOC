#How-To Use

1. Clone this repo
2. Install Pillar

		./download.sh

3. Patch Pillar by loading package Pillar-ExporterCore-LucFabresse.381 from repository

		MCHttpRepository
			location: 'http://smalltalkhub.com/mc/Pier/Pillar/main'
			user: ''
			password: ''

4. Compile :

		make
		# or just one slides
		make book-result/Slides/1-ToReview/Basic-Numbers.pdf
		
5. See results in book-result ;-)
