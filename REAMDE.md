Kata Challenge
	
	1. Identify the Internal component

			ReservationHandler

			TripHandler

			DeviceHandler

			EMailHanlder

	2. Assign the Requirement to respective component.

			
			TripHandler
				Allow track booked ticket.

			DeviceHandler

				Support device

			EmailHandler

				Send alerts on reservation

	3. Analise the roles and responsibility of each component

			TripHandler

				User login


						Allow user to login / Sing up to application.

						Allow user to add/update/delete existing reservation.

							To Add Travel detail -> 

								Allow to search for predefined Agencies.

								Allow to enter new agency URL by selecting other option.

						Provide user feedback section

						Sort/Filet trips

						Generate trip report (Canceled , upcoming, Travel Agency)

						Help Me (for FAQ)

						I18N


				Only for admin user

						Allow to add traveler agency

						Allow to update travel details (like booking, delay, cancellation ...etc)

						Handle  user/passenger query/information.

						Get year/half year/quarter trip details report

						Send analysis report to user by email (quaterly / half / year)

			DeviceHandler

				allow to support types of device from user can use this application.

	4. Analyze architecture characteristic

			As we need to get many information we can go with distributed architecture. (micro service architecture)

			As it is web based application go with technical partition based on the component required for each functionality.
