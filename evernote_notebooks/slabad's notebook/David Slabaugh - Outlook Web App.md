
alter table OrderHeader add FromLeadPool bit not null default 0

This would be on both MTO and MTOCart. This helps me fulfill a requirement at connect@checkout that if the consultant assignment came from the leadpool, that we don’t allow the user to switch consultant on the order. I also wanted to add it to the MTO schema because this would allow the business to track exactly which orders came from the lead pool.

I’ve added the columns to dev and will be adding them to the data schema in my branch. Dave, all you need to do is update your ERD with the definition above.

Thanks,

Nate

    Created at: 2014-09-25T10:35:48-04:00
    Updated at: 2014-09-25T10:35:48-04:00

