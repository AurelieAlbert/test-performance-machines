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
            <td rowspan=4>Opening of netcdf -  10Tb</td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td>9.53s</td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
         <tr>
            <td rowspan=4>Opening of zarr -  10Tb</td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td>9.53s</td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td rowspan=4>Wavenumber-frequency spectrum of KE </td>
             <td>Personnal Computer</td>
             <td>8 cores - 34Gb</td>
             <td>9.53s</td>
        </tr>
        <tr>
            <td>Cluster cal1</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC hal CNES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
        <tr>
            <td>HPC occigen CINES</td>
            <td>8 cores - 34Gb</td>
            <td>9.53s</td>
        </tr>
    </tbody>
</table>
