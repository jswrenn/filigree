# A Bitsharing Cooperative
As with any cooperative, in which members pool their resources together
for a reward greater than the sum of its parts, a bitshare is a
community that shares computing and storage resources. 

Filigree is a bitsharing cooperative for sharing storage that seeks
to deliver the benefits of cloud data storage in a drastically more
transparent and communal manner. For most people, cloud data storage
is the only inexpensive way to secure personal files against the risks
of data loss, but at the cost of sacrificing control over one's data.
For most people, replicating the industry best-practices for data
storage at home is prohibitively expensive. That is, until now. 

Members of filigree donate operative control of a small computing device
(but retrain ownership and possession) that is used as node in a cluster
running a distributed replicated filesystem. In return, they receive
access to a fault-tolerant storage cluster (potentially many terabytes
in size). In the spirit of a coop, this storages space is a shared pool.

# Filament: The Filigree Appliance
The filigree cluster is composed of small, member-owned computers called
**filaments**. Potentially, any device might be contributed to the coop
so long as it can, by whatever standards the coop members agree upon,
"pull its own weight". We define a filament as a device having 5Tb of
available storage, 4Gb of memory, and an x86-64 processor. We provide
a reference filament which users may buy at the cost of parts.

![NUC](https://www-ssl.intel.com/content/dam/www/public/us/en/images/product/nuc-board-de3815tybe-2x1.jpg/jcr:content/renditions/cq5dam.web.1280.1280.jpeg?cq_ck=1396496209000)

Filament is a Intel® NUC Board DE3815TYBE (pictured above), modified
to support the power draw of a standard-sized SATA power connector and
a custom case to accomodate a 3.5" HDD.
