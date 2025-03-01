# Dataset descriptions
Both <code>train.csv</code> and `test.csv` contain one row for each unique subscription. For each subscription, a single observation (CustomerID) is included during which the subscription was active.

In addition to this identifier column, the train.csv dataset also contains the target label for the task, a binary column Churn.

Besides that column, both datasets have an identical set of features that can be used to train models to make predictions. Below you can see descriptions of each feature.


| Column Name               | Column Type   | Data Type | Description                                           |
|---------------------------|---------------|-----------|-------------------------------------------------------|
| AccountAge                | Feature       | integer   | The age of the user's account in months.             |
| MonthlyCharges            | Feature       | float     | The amount charged to the user on a monthly basis.    |
| TotalCharges              | Feature       | float     | The total charges incurred by the user over the account's lifetime. |
| SubscriptionType          | Feature       | object    | The type of subscription chosen by the user (Basic, Standard, or Premium). |
| PaymentMethod             | Feature       | string    | The method of payment used by the user.              |
| PaperlessBilling          | Feature       | string    | Indicates whether the user has opted for paperless billing (Yes or No). |
| ContentType               | Feature       | string    | The type of content preferred by the user (Movies, TV Shows, or Both). |
| MultiDeviceAccess         | Feature       | string    | Indicates whether the user has access to the service on multiple devices (Yes or No). |
| DeviceRegistered          | Feature       | string    | The type of device registered by the user (TV, Mobile, Tablet, or Computer). |
| ViewingHoursPerWeek       | Feature       | float     | The number of hours the user spends watching content per week. |
| AverageViewingDuration    | Feature       | float     | The average duration of each viewing session in minutes. |
| ContentDownloadsPerMonth  | Feature       | integer   | The number of content downloads by the user per month. |
| GenrePreference           | Feature       | string    | The preferred genre of content chosen by the user.    |
| UserRating                | Feature       | float     | The user's rating for the service on a scale of 1 to 5. |
| SupportTicketsPerMonth    | Feature       | integer   | The number of support tickets raised by the user per month. |
| Gender                    | Feature       | string    | The gender of the user (Male or Female).             |
| WatchlistSize             | Feature       | float     | The number of items in the user's watchlist.         |
| ParentalControl           | Feature       | string    | Indicates whether parental control is enabled for the user (Yes or No). |
| SubtitlesEnabled          | Feature       | string    | Indicates whether subtitles are enabled for the user (Yes or No). |
| CustomerID                | Identifier    | string    | A unique identifier for each customer.               |
| Churn                     | Target        | integer   | The target variable indicating whether a user has churned or not (1 for churned, 0 for not churned). |


