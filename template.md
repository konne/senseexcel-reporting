# Example outputFormat options -> delimiter

template: 
{
            input: content:///ExecutiveDashboard.xlsx
            output: ='Report_'&only(Region)&'_'&max([Fiscal Year])&'.csv'
            outputFormatOptions: {separator: '|'}
}
