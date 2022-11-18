# file-report-on-program-zktime
begin   if IsHoliday(ReportStartDate+23) then     fillcolor := HolidayColor   else if IsWeekEnd(ReportStartDate+23) then     FillColor := WeekendReportColor;  end
