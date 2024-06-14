# Matomo Goal Conversion Export Plugin for Matomo V5 (beta testing)

## License

GPL v3 or later


# Manual adding Goal (for Google Ads)

As the UI no longer works in Matomo V5 and the original plug-in hasn't been updated for a long time, I created this fork to keep my Matomo up to date. I haven't managed to fix the UI, so in the meantime here are the instructions for using it without the UI.

## Add Goal

Goto database table xxxx_goal_conversion_export and add a export

| Parameter | content | Note |
| :--------------- |:---------------| :-----|
| access_token | Example: h2s6h5z2h6sd2g  | Used in export URL |
| name | Choose a name for this export |  |
| export_type | "google" or "facebook" |  |
| description | Choose a description for this export" |  |
| goals | ```[{"id_goal":"1","export_name":"<goal_name_1>","revenu":"null"},{"id_goal":"2","export_name":"<goal_name_1>","revenu":"null"}, ... ]``` | **id_goal**: ID of Goal, **export_name**: name in Google Ads |
| day_to_export | put "1" if you want 1 import per days | |


## URL for EXPORT:

https://mymatomo.com/index.php?module=GoalConversionExport&action=generateConversionExport&accessToken=xxxxxxxxxxxxxx

xxxxxxxxxxxxxx = Access token put in xxxx_goal_conversion_export


# Description

### Overview

The Matomo Goal Conversion Export Plugin is a powerful tool designed to enhance your digital marketing efforts. This
plugin enables you to export attributed goal conversions from your Matomo analytics data, making it easy to integrate
this valuable information into ad networks such as Google Ads and Meta Ads.

### Features

- **Export Goal Conversions**: This plugin allows you to seamlessly export goal conversions from Matomo, ensuring you
  have access to accurate and attributed data for your marketing campaigns.

- **Attribution Tracking**: Gain insights into the source and medium of each goal conversion, helping you understand
  which channels and campaigns are driving the most conversions.

- **Flexible Export Formats**: The plugin supports a range of export formats, making it compatible with popular ad
  networks
  and analytics platforms. Choose the format that best suits your needs.

- **Customizable Export Periods**: Export data for specific time frames, allowing you to focus on relevant data for your
  ad network campaigns.

- **Easy Integration**: Integrate the exported data effortlessly with Google Ads, Meta Ads, or any other advertising
  platform that supports the chosen export format.

# How to Use

1. **Installation**: Install the Matomo Goal Conversion Exporter Plugin within your Matomo instance. Follow the
   installation instructions provided with the plugin.

2. **Configuration**: Configure the plugin to specify the export format and customize the time frames for data export.

3. **Export Data**: Use the plugin to export attributed goal conversion data from your Matomo analytics.

4. **Integration**: Import the exported data into your ad networks like Google Ads and Meta Ads, ensuring that your
   campaigns benefit from informed decision-making.