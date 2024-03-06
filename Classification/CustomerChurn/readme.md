Column_name	Column_type	Data_type	Description
0	AccountAge	Feature	integer	The age of the user's account in months.
1	MonthlyCharges	Feature	float	The amount charged to the user on a monthly basis.
2	TotalCharges	Feature	float	The total charges incurred by the user over the account's lifetime.
3	SubscriptionType	Feature	object	The type of subscription chosen by the user (Basic, Standard, or Premium).
4	PaymentMethod	Feature	string	The method of payment used by the user.
5	PaperlessBilling	Feature	string	Indicates whether the user has opted for paperless billing (Yes or No).
6	ContentType	Feature	string	The type of content preferred by the user (Movies, TV Shows, or Both).
7	MultiDeviceAccess	Feature	string	Indicates whether the user has access to the service on multiple devices (Yes or No).
8	DeviceRegistered	Feature	string	The type of device registered by the user (TV, Mobile, Tablet, or Computer).
9	ViewingHoursPerWeek	Feature	float	The number of hours the user spends watching content per week.
10	AverageViewingDuration	Feature	float	The average duration of each viewing session in minutes.
11	ContentDownloadsPerMonth	Feature	integer	The number of content downloads by the user per month.
12	GenrePreference	Feature	string	The preferred genre of content chosen by the user.
13	UserRating	Feature	float	The user's rating for the service on a scale of 1 to 5.
14	SupportTicketsPerMonth	Feature	integer	The number of support tickets raised by the user per month.
15	Gender	Feature	string	The gender of the user (Male or Female).
16	WatchlistSize	Feature	float	The number of items in the user's watchlist.
17	ParentalControl	Feature	string	Indicates whether parental control is enabled for the user (Yes or No).
18	SubtitlesEnabled	Feature	string	Indicates whether subtitles are enabled for the user (Yes or No).
19	CustomerID	Identifier	string	A unique identifier for each customer.
20	Churn	Target	integer	The target variable indicating whether a user has churned or not (1 for churned, 0 for not churned).
