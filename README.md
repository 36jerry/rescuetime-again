# Why

[RescueTime](https://www.rescuetime.com) is a fantastic tool for time management.
I mainly use it to understand my daily habits so I can become more productive.

Unfortunately, the free version doesn't have as much in-depth analysis as I would like. So I built my own charts using their API to access RescueTime's data!

If you have any suggestions for new features, please send me an email.

For the best results, be sure to categorize each activity on RescueTime!

If you would like to use the old version, [go here!](http://ilbonte.github.io/rescuetime-again/old/)

# Usage

1.  Navigate to the [project page](http://ilbonte.github.io/rescuetime-again/).
2.  Select your data source by either:
  * Pulling data directly from RescueTime using their API key.
  * or Uploading your JSON Files containing your RescueTime data ([see below](#workaround) for more information)
3.  ????
4.  PROFIT! 💰

## Notes

RescueTime's free plan allows you to see only the last three months of data. So if you don't own a premium account, be sure to select a range within 3 months of the current date.

<a name="workaround"></a>
If you have a free plan and you would like to analyse a period *longer* than 3 months, there is a "workaround":
* From the [project page](http://ilbonte.github.io/rescuetime-again/), you can tick the box to download the JSON file containing data for the selected range. I usually download my data once a month (e.g. in May, I download the data for April) and store the files in Dropbox. ([watch video 0:13](https://drive.google.com/open?id=0B5suZDyzIrpOcl91U0l4LU1jOEU))
* Once you have downloaded enough files for your desired range, you can then merge them into a single file to analyse it through the main page. ([watch video 0:25](https://drive.google.com/open?id=0B5suZDyzIrpOaTNZNE16QzJoVXc))
* To merge the JSON files, go to the [merge page](https://ilbonte.github.io/rescuetime-again/merge.html) and select the file you would like to merge. Note that the files must all be of the same type (efficiency or activity). ⚠️ ***You cannot merge efficiency and activities! ***([watch video 0:29](https://drive.google.com/open?id=0B5suZDyzIrpOM2pPcmxYenpYSTg))


## Contributing

Pull requests for bug fixes are welcome. If you want to add a new feature, just open an issue beforehand so we can discuss the feature together.

## [Change Log 📋 ](https://github.com/ilbonte/rescuetime-again/blob/gh-pages/CHANGELOG.md)

### Example
Example displaying 16 months of RescueTime data.
![alt tag](http://i.imgur.com/PptwdMU.png)
