# Bio Inspired Heliotropic Solar Cell system
The purpose of this project is to develop a system that helps optimize the light energy
absorbed by the solar panels deployed.The method discussed is to continuously or
discreetly change the angles of the solar panel so that it coordinates with the incident
light rays from the sun and maintains an angle such that it results in maximum
absorption of light and as a result maximum energy generation.

# Abstract
The report focuses on development of framework and design for mechanically
automated heliotropic solar cells. The project does not focus on changing the chemical
compositions of the existing industry standard solar cells or their arrangement design
patterns.The project focuses on maximizing the solar energy absorbed by making an
optimal incidence angle at all times with the incoming rays of sunlight.To achieve
variable angles throughout the day we designed a robotic structure which helps the
solar plates move between the restricted angles through the day,To achieve this we
introduce 2 methodologies which uses a linear regression algorithm working for
deciding optimal angle at all the time, this kind of approach is suitable for place with
highly varying weather and inconsistent climate conditions as the other method does not
make use of any ML algorithm, instead it is fed a fixed route of movement throughout
the day.Both of these methods to make the solar plates more efficient have their own
advantages and disadvantages discussed later in the report.To implement the
movement we have proposed to use servo motor attached to a moving joint where the
solar panel is attached.To track the movement of the sunlight focus throughout the day
we have taken a separate device to isolate the error possibilities from the solar panel
module and make the overall system to be scalable as well as fault
tolerant.Theoretically the system should be atleast 29.3%, if we calculate the lost
energy due the incident angle,and only assume half of it is usable in form of electricity
due multiple losses.
