@brief 		How to perform multiple backups
@details 	This procedure is quite tricky and not expected
@date 		12/04/17

@section 	
	@pre	Backup must be encrypted
	1. Close iTunes
	2. Change Dir Name
		@note	dir name is static and reflects phone ID
		e.g. '093c8dd1d601c5770673300e885c707ec1a76e62'
		to '093c8dd1d601c5770673300e885c707ec1a76e62_YY_MM_DD'
	3. Change Name (info.plist)
		<key>Device Name (MM/DD/YY)</key>
		<string>iPhone</string>
		<key>Display Name (MM/DD/YY)</key>
		<string>iPhone</string>


@section 	Result
	Close and re-open iTunes, new backup copy will appear in backups