# test-performance-machines

In this repo a collection of notebooks that have been run on various machine : local machine, cluster cal1, pangeo cloud, hal cines HPC and occigen cines HPC.

The results are :


<table>
    <thead>
        <tr>
            <th>Operation</th>
            <th>Machine</th>
            <th>Ressources</th>
            <th>Timing</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Opening of netcdf -  1Tb</td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td>30min</td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>20 cores - 62Gb</td>
            <td> 2min </td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>48 cores - 240Gb</td>
            <td>36mn</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>PANGEO cloud</td>
            <td>20 cores - 115Gb</td>
            <td> X </td>
        </tr>
         <tr>
            <td rowspan=5>Opening of zarr -  1Tb</td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td>8s</td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>20 cores - 62Gb</td>
            <td> 12s </td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>48 cores - 240Gb</td>
            <td>11s</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>PANGEO cloud</td>
            <td>20 cores - 115Gb</td>
            <td>8min</td>
        </tr>
        <tr>
            <td rowspan=5>Wavenumber-frequency spectrum of KE </td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td> X </td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>20 cores - 62Gb</td>
            <td> X </td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>48 cores - 240Gb</td>
            <td>18min</td>
        </tr>
        <tr>
            <td>PANGEO cloud</td>
            <td>20 cores - 115Gb</td>
            <td>22min</td>
        </tr>
    </tbody>
</table>
