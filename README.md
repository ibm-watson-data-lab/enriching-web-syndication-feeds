# enriching-web-syndication-feeds

* [Provision an instance of the Watson Natural Language service in Bluemix](https://console.bluemix.net/catalog/services/natural-language-understanding/) (use the _Lite_ plan, which is free!)
* Load [this notebook](https://raw.githubusercontent.com/ibm-watson-data-lab/enriching-web-syndication-feeds/master/enrich_syndication_feed%20PUBLIC.ipynb) into a project in [Data Science Experience](http://datascience.ibm.com/analytics) ([Instructions](https://apsportal.ibm.com/docs/content/analyze-data/creating-notebooks.html)) 
* Customize the `feed_url` (cell 2), if desired
  ```
  feed_url = 'http://feeds.feedburner.com/freakonomicsradio'
  ```
* Enter the credentials of your Watson Natural Language service instance in cell 3.
  ```
  # @hidden_cell
  # TODO: replace with your Watson Natural Language Understanding service credentials (https://console.bluemix.net/catalog/services/natural-language-understanding/)
  nlu_credentials = {
      "url": "https://gateway.watsonplatform.net/natural-language-understanding/api",
      "username": "my_nlu_username",
      "password": "my_nlu_password"
  }
  ```
* Run all cells

