## page1 表紙

## page2 CNCF Logo

## page3
“I’m bored Aunt Phippy,” Zee slouched further down on the couch. “What are we going to do today?”

“Why not go see the animals?” said Phippy with a smile. “We’ll go to the zoo!”

"Yeah!" Zee let out a whoop and ran to find some shoes.

## page4
The first animals they came upon were the size of squirrels. Furry and blue, each little animal carried a tiny box as they unceasingly zipped back and forth. 

“Those,” said Phippy, “are Pods. All day and all night, they run back and forth carrying their little containers.”
“Is that all they do, Aunt Phippy?”

“Yup, Zee. For their entire lives, that’s all the Pods do. They run.”

## page5
In Kubernetes, Pods are responsible for running your containers. Every Pod holds at least one container, and controls the execution of that container. When the containers exit, the Pod dies too.

## page6
As Phippy and Zee walked on, they saw a large glass enclosure. Pressed against the window was a line of happy little meerkat faces. “Those are the ReplicaSets,” said Phippy.  

As Zee watched, the face on the right grinned widely, and tipped itself off the ledge. In unison, the others hopped over to fill the space, and then an identical meerkat scurried up on the left side.  

“Every time one little replica falls, another one hops right up,” explained Phippy. 

## page7
A ReplicaSet ensures that a set of identically configured Pods are running at the desired replica count. If a Pod drops off, the ReplicaSet brings a new one online as a replacement.

## page8
Walking further, Zee pointed out a clump of burrows and warrens. While there were plenty of signs that the area was inhabited, neither Phippy nor Zee could see a single movement. 

“The Secrets are in here,” said Phippy. “but you can’t see them without these decoder glasses.” 

Zee took the pair of glasses Phippy offered, slid them on, and blushed. “Oh, my. I think I’m ready to go on now, Aunt Phippy.” Zee handed back the glasses, and onward they went. 

## page9
Secrets are used to store non-public information, such as tokens, certificates, or passwords. Secrets can be attached to Pods at runtime so that sensitive configuration data can be stored securely in the cluster.

## page10
A group of iguanas gathered near a large slingshot along the shore of a pond. An island stood in the center of the water. An iguana threw herself into the slingshot and the other iguanas launched the little beast toward the island.    

“The Deployments release a group onto the island. Right now, they’re trying to get three out there.” said Phippy.

At that moment another iguana rocketed into the air but missed the island with a colossal splash in the pond.  

Phippy said, “If they miss, they just keep trying until they get as many as they need.”

## page11
A Deployment is a higher-order abstraction that controls deploying and maintaining a set of Pods. Behind the scenes, it uses a ReplicaSet to keep the Pods running, but it offers sophisticated logic for deploying, updating, and scaling a set of Pods within a cluster.

## page12
Several stone pillars arose from a grassy knoll and at the top of each sat a vulture. As Zee and Phippy watched, one vulture spread its wings and flapped off into the distance. No sooner had one left than another took its place. Zee asked, “What are they doing?” 

“Those are DaemonSets,” said Phippy, “They make sure to occupy every pillar, rain or shine, day or night.” 

“I bet that if we added a new pillar, a new bird would land on it faster than you could say ‘cube cuddle,’” chuckled Phippy. 

## page13
DaemonSets provide a way to ensure that a copy of a Pod is running on every node in the cluster. As a cluster grows and shrinks, the DaemonSet spreads these specially labeled Pods across all of the nodes.

## page14

As they walked on, they saw an aquarium with an enormous reef. Edge-to-edge, it appeared that the rock would keep anything from passing from one side to the other. Zee watched as hundreds of tiny fish made a dash for the center of the face of the rock. At full speed, the fish swam into a hole bored into the rock face and momentarily vanished from sight.  

Zee let out a gasp. Multicolored flashes erupted from the opposite side of the coral. Instead of coming out of a single hole, the fish seemed to materialize from tiny fissures all over the far side of the rock.  

“Ingresses are beautiful,” said a dreamy eyed Phippy.  

Enchanted, Zee muttered, “Uh-huh.”

## page15
Ingresses provide a way to declare that traffic ought to be channeled from the outside of the cluster into destination points within the cluster. One single external Ingress point can accept traffic destined to many different internal services.

## page16
Zee pointed to the raccoons sprawled motionless in the next enclosure. “What’s wrong with them?” 

Suddenly, one sprung to its feet, did jumping jacks, then settled back down for another nap. 

“Those are CronJobs,” said Phippy. “Mostly, they just sleep. But periodically, they spring into action to do a specific job.” 

As she spoke, another bolted upright, grabbed a broom, swept the entire enclosure, and then dropped off to sleep again. “Aunt Phippy, can I bring that one home to clean my room?” Phippy laughed as they walked on.

## page17
CronJobs provide a method for scheduling the execution of Pods. They are excellent for running periodic tasks like backups, reports, and automated tests.

## page18
Zee halted abruptly. In the distance, a black-railed fence arose. The arches above the pen were marked C-R-D. Between the bars, Zee could make out some peculiar critters. A giraffe with a hippopotamus head. A snake with raccoon ears. A lion with a beaver’s tail. A unicorn with no horn. Zee wasn’t sure she liked the looks of that place. 

“Oh,” said Phippy, a look of concern on her face, “Uh… look! It’s lunch time! We’d better head home.” 

With a look of mild relief, Zee complied. “Can we stop at Captain Kube’s Shake Shop on the way out?”

## page19
CustomResourceDefinitions, or CRDs, provide an extension mechanism that cluster operators and developers can use to create their own resource types.




