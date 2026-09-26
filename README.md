[![Foto Preview](preview/project-1413.avif)](https://the-booking-d960960gm-0b09.wix-site-host.com/)

<div align="center" style="display: flex; justify-content: center;">
  <a  href="https://github.com/20essentials/project-1412" target="_blank">&#8592;</a>
  &nbsp;&nbsp;
  <a  href="https://github.com/20essentials/project-1414" target="_blank">&#8594;</a>
</div>

## Wix Astro Scheduler 

An appointment scheduling project built with Astro and [Wix Bookings](https://dev.wix.com/docs/sdk/backend-modules/bookings/introduction). It demonstrates the full booking flow against a Wix site:

- Listing bookable services with `@wix/bookings` (`services.queryServices`)
- Fetching availability in the visitor's timezone (`availabilityCalendar.queryAvailability`)
- Creating bookings for free services (`bookings.createBooking` + `@wix/ecom` cart)
- Redirecting to the Wix-hosted checkout for paid services (`@wix/redirects`)

The Wix integration logic lives in `src/utils/booking-service.ts`; pages are in `src/pages` (home, schedule, confirmation, 404).

## Need help?

- [Wix Headless Documentation](https://dev.wix.com/docs/go-headless)
- [Wix SDK Documentation](https://dev.wix.com/docs/sdk)
